# bw

login to bitwarden:
```bash
bw login
```

unlock bitwarden:
```bash
bw unlock
```

list all items:
```bash
bw list items
```

search for a password:
```bash
bw list items --search ca2af4af-42cb-4a5d-a236-ad0d0c5365cc | jq '.[0].login.password'
```

