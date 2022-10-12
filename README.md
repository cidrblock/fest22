# ansible-fest 2022

Build the new execution environment
```
cd builder
ansible-navigator builder build --tag fest22 -v 3
```

Ensure we are at the root of repository
```
cd ..
```

Run ansible-navigator
```
ansible-navigator
```

Show current settings
```
:settings
```

Browser images
```
:images
```

Show collections
```
:collections
```

Run the playbook
```
:run site.yaml
```

Some notable settings for navigator
- The editor is set to code
- The execution environment is set to fest22
- Log files are written to the log directory and ignored by git
- Playbook artifacts are written to the artifacts directory and gitignored

