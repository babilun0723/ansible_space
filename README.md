## anisble_space


**anisble_space folder structure**

```
hosts
playbooks
roles/
    <roleName>/
        tasks/
        handlers/
        files/
        templates/
        vars/
        defaults/
        meta/
templates/
```    
  
**example**
```shell
cd ansible_space

ansible-playbook -i hosts playbooks/scrapy.yml -sudo
```
