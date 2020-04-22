## Listing Hosts
all hosts
`ansible --list-hosts all`
globbinig is allows
`ansible --list-hosts "foo*"`
everything but
`ansible --list-hosts "!foo"`
by host index
`ansible --list-hosts "foo[1]"`



## Pinging
`ansible -m ping all`
