# Cheatsheets

## Run ansible with specific tag

```sh
ansible-playbook --ask-become-pass -i inventories/localhost playbook.yml --tag packages
```

## Troubleshoot exim4

### Test if mail setting is correct

```sh
echo "hello" | mail -s "Test" thebangnguyen@gmail.com
```

### Tail exim4 log

```sh
sudo tail -f /var/log/exim4/mainlog
```

### Change client password

```sh
sudo vi /etc/exim4/passwd.client
```

and update the password to the googleone

### Restart exim4

```sh
sudo service exim4 restart
```
