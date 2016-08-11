## Ansible alpine images (size 80Mb,Compressed 25Mb)

## Usage
Go to your ansible directory

`docker run --rm  -v "$PWD":/ansible yikaus/ansible-playbook test.yml`

Run other ansible command 

`docker run --rm  -v "$PWD":/ansible --entrypoint ansible-vault yikaus/ansible-playbook `

Check version

`docker run --rm yikaus/ansible-playbook --version`
```
ansible-playbook 2.1.1.0
  config file = 
  configured module search path = Default w/o overrides
```

Feel free to modify Dockerfile install the version you needed 

## License
MIT