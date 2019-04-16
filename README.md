Simple role for managing OpenSSH configuration.  
Default parameters:

```
openssh_config_path: "/etc/ssh/sshd_config"
openssh_daemon_name: "ssh"
openssh_port: "22"
openssh_password_authentication: "no"
openssh_permit_root_login: "without-password"
openssh_usedns: "no"
openssh_permit_empty_passwords: "no"
openssh_challenge_response_auth: "no"
openssh_gss_api_authentication: "no"
openssh_x11_forwarding: "no"
openssh_kexalgorithms: "diffie-hellman-group-exchange-sha256"
openssh_macs: "hmac-sha2-512,hmac-sha2-256"
openssh_ciphers: "aes256-ctr,aes192-ctr,aes128-ctr"
```

For network banners specify openssh_banner like this:

```
