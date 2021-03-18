# what-is-psexec

## what is psexec?

## conventions

- `LOCAL`. refers to the local machine (the machine the sysadmin sits in front of).
- `REMOTE`. refers to the remote machine that is being administrated by the sysadmin.

## how does psexec work?

- requirements for psexec:
  - `LOCAL`
    - A modern Windows computer
  - `REMOTE`
    - _File and Printer Sharing (SMB protocol)_ open (TCP port 445)
    - The `admin$` administrative share available on `REMOTE`
    - a local account’s credential on `REMOTE`

## references
- [Psexec: the ultimate guide](https://adamtheautomator.com/psexec/)
