# Ansible - awscli

aws-cli on your ubuntu machine


## Role Variables

These are the default role variables.

```
aws_ssh_user: '{{ ansible_ssh_user }}'
aws_home_dir: '/home/{{ aws_ssh_user }}'
aws_region: 'eu-west-1'
aws_access_key_id: 'XXX'
aws_secret_access_key: 'XXX'
```


## Contributing

Want to contribute? Awesome. Just send a pull request.


## License

ansible-awscli is released under the [MIT License](http://www.opensource.org/licenses/MIT).
