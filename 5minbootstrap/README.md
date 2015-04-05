Customized version of https://github.com/robfeldmann/5-min-bootstrap/

differences :

  - works for ansible 1.8.x
  - use `{{ lookup('file', <PATH> }}`
  - use `service: name=sshd state=restarted`

