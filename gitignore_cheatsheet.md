| Pattern       | Explanation                                           | Example       |
| ------------- | ----------------------------------------------------- | ------------- |
| `file.txt`    | Ignore a specific file named `file.txt`               | `file.txt`    |
| `folder/`     | Ignore all files and subdirectories in `folder/`      | `folder/`     |
| `*.txt`       | Ignore all files with the `.txt` extension            | `*.txt`       |
| `*.log`       | Ignore all log files                                  | `*.log`       |
| `*.zip`       | Ignore all zip archives                               | `*.zip`       |
| `*~`          | Ignore all files ending with `~`                      | `*~`          |
| `!file.txt`   | Include `file.txt` even if it matches a previous rule | `!file.txt`   |
| `/logs/*.log` | Ignore all log files in the `logs/` directory         | `/logs/*.log` |
