<p align="center">
	<img src="https://www.chatwoot.com/docs/img/logo.png" alt="Chatwoot-logo" width="100" />	
	<p align="center">O Chatwoot oferece todas as ferramentas para gerenciar conversas, construir relacionamentos e encantar seus clientes em um só lugar.</p>
</p>

<p align="left">
	<img src="https://whatsapp.com/favicon.ico" alt="WhatsAPP-logo" width="32" />
	<span>Grupo WhatsaAPP: </span>
	<a href="https://chat.whatsapp.com/CLKge3hmHmmBcIL04mBzmT" target="_blank">Grupo</a>
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
