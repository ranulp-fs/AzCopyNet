## azcopy jobs remove

Remove all files associated with the given job ID.

### Synopsis


Remove all files associated with the given job ID.

Note that you can customize the location where log and plan files are saved. See the env command to learn more.

```
azcopy jobs remove [jobID] [flags]
```

### Examples

```
  azcopy jobs rm e52247de-0323-b14d-4cc8-76e0be2e2d44
```

### Options

```
  -h, --help   help for remove
```

### Options inherited from parent commands

```
      --cap-mbps float                      Caps the transfer rate, in megabits per second. Moment-by-moment throughput might vary slightly from the cap. If this option is set to zero, or it is omitted, the throughput isn't capped.
      --log-level string                    Define the log verbosity for the log file, available levels: INFO(all requests/responses), WARNING(slow responses), ERROR(only failed requests), and NONE(no output logs). (default 'INFO'). (default "INFO")
      --output-level string                 Define the output verbosity. Available levels: essential, quiet. (default "default")
      --output-type string                  Format of the command's output. The choices include: text, json. The default value is 'text'. (default "text")
      --trusted-microsoft-suffixes string   Specifies additional domain suffixes where Azure Active Directory login tokens may be sent.  The default is '*.core.windows.net;*.core.chinacloudapi.cn;*.core.cloudapi.de;*.core.usgovcloudapi.net;*.storage.azure.net'. Any listed here are added to the default. For security, you should only put Microsoft Azure domains here. Separate multiple entries with semi-colons.
```

### SEE ALSO

* [azcopy jobs](azcopy_jobs.md)	 - Sub-commands related to managing jobs

###### Auto generated by spf13/cobra on 15-Dec-2022
