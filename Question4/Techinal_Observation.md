## Creating the workspace

I created a separate folder to store the report, screenshots, and observations for the file I/O investigation.

## Command: lsof | head -20

The `lsof` command lists files currently opened by running processes. It helps identify which files and devices are actively being used.

## Command: ls -l /dev/fd

The `/dev/fd` directory provides access to the file descriptors opened by the current process. It illustrates how Linux/Unix represents open files through file descriptors.

## Output Redirection

The `>` operator redirects standard output (stdout) from the terminal into a file instead of displaying it on the screen.

## Error Redirection

The `2>` operator redirects standard error (stderr) into a file while preventing the error from appearing on the terminal.

## Command: ulimit -a

The `ulimit -a` command displays the resource limits for the current shell, including limits on open files, processes, memory, and CPU time.
