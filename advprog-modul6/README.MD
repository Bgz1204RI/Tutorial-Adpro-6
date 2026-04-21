# Commit 1 Reflection notes
- explain what `TcpListener::bind` does
- explain what `incoming()` returns
- explain why browser requests cause "Connection established!"
- explain why nothing appears in browser yet
- explain why `_stream` avoids warning
- explain what you learned

# Commit 2 Reflection notes
- explain `BufReader`
- explain `.lines()`
- explain why HTTP response needs status line + headers + body
- explain `Content-Length`
- explain why `hello.html` must be in project root
- explain what changed from commit 1

# Commit 3 Reflection notes
- explain `request_line`
- explain matching `GET / HTTP/1.1`
- explain 404 handling
- explain why refactoring into `(status_line, filename)` is cleaner
- explain how browser behavior changes
- explain what you learned

# Commit 4 Reflection notes
- explain why `/sleep` delays 10 seconds
- explain why single-threaded server blocks other requests
- explain what you observed with two tabs
- explain why this is bad for many users
- explain why concurrency is needed
- explain what you learned

# Commit 5 Reflection notes
- explain what `ThreadPool` is
- explain why using a fixed number of workers is better than spawning unlimited threads
- explain `mpsc`, `Arc`, `Mutex`
- explain how jobs are sent to workers
- explain why multithreading fixes the blocking issue better
- explain what you learned