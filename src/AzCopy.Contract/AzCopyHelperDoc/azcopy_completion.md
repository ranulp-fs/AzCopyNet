## azcopy completion

Generate the autocompletion script for the specified shell

### Synopsis

Generate the autocompletion script for azcopy for the specified shell.
See each sub-command's help for details on how to use the generated script.


### Options

```
  -h, --help   help for completion
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

* [azcopy](azcopy.md)	 - AzCopy is a command line tool that moves data into and out of Azure Storage.
* [azcopy completion bash](azcopy_completion_bash.md)	 - Generate the autocompletion script for bash
* [azcopy completion fish](azcopy_completion_fish.md)	 - Generate the autocompletion script for fish
* [azcopy completion powershell](azcopy_completion_powershell.md)	 - Generate the autocompletion script for powershell
* [azcopy completion zsh](azcopy_completion_zsh.md)	 - Generate the autocompletion script for zsh

###### Auto generated by spf13/cobra on 15-Dec-2022
