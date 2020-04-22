## Listing Hosts
all hosts
`ansible --list-hosts all`
globbinig is allows
`ansible --list-hosts "foo*"`
everything but
`ansible --list-hosts "!foo"`
by host index
`ansible --list-hosts "foo[1]"`


> not the these commands are all refering to a module
## Pinging
`ansible -m ping all`
> ping module
## Command
`ansible -m command -a "hostname" all`
> command module (default)