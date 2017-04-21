# yum_proxy

An Ansible role that configures yum to use the specified proxy server.


## Role Variables

* `yum_proxy_url: ''` - a proxy server URL, an existent proxy server settings
                        will be removed from config if it's not defined.


## Example Playbook

```yaml
    ---
    - hosts: all
      roles:
        - { role: ezamriy.yum_proxy, yum_proxy_url: 'http://192.168.1.1:3128/' }
```


## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
