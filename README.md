<p align="center">
<img src="https://cwmkt.com.br/wp-content/uploads/2024/04/logo_github.png" width="240" />
<p align="center">Seja bem-vindo ao Guia de atualização Teste SMTP 🚀</p>
</p>
  
<p align="center"> 
<a href="https://hubconnect.top" target="_blank">👉 Participe da Comunidade HubConnect 👈</a>
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
mailer.delivery_method = :smtp
mailer.smtp_settings = smtp_settings

mailer.mail(from: 'remetente@email.com', to: 'destinario@email.com', subject: 'test', body: "Hello, you've got mail!").deliver
```

<hr />
<hr />
