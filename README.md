###### git clone from https://github.com/babilun0723

## anisble_space


**anisble_space folder structure**

```
<lifecyclename>   --Such as test
     host
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
