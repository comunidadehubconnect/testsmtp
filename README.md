<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2023/08/logo-github-cwmkt.svg" alt="DispZap Whats Marketing" width="240" />
<p align="center">Seja bem-vindo ao Guia de atualização do n8n, nodejs e quepasa 🚀</p>
</p>
  
<p align="center">
<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
<span>Grupo WhatsaAPP: </span>
<a href="https://link.cwmkt.com.br/grupo-whats" target="_blank">Grupo</a>
</p>

<hr />
<hr />

**Teste de SMTP**

```bash
cwctl --console
```

```bash
ActionMailer::Base.smtp_settings
```

```bash
# Fill values for appropriate settings
# Remove the keys which aren't relevant to your use case
smtp_settings = {
  address: '',
  port: '',
  user_name: '',
  password: '',
  domain: '',
  tls: '',
  enable_starttls_auto: '',
  openssl_verify_mode: '',
  authentication: '',
}

mailer = ActionMailer::Base.new
# check settings:
mailer.delivery_method = :smtp
mailer.smtp_settings = smtp_settings

# replace with your values for the mail
mailer.mail(from: 'remetente@email.com', to: 'destinario@email.com', subject: 'test', body: "Hello, you've got mail!").deliver
```

<hr />
<hr />
