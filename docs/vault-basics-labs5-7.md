name: vault-basics-labs1-4
class: title, shelf, no-footer, fullbleed
background-image: url(https://hashicorp.github.io/field-workshops-assets/assets/bkgs/HashiCorp-Title-bkg.jpeg)
count: false

---
name: lab-vault-basics-challenge-5
# 👩‍💻 Challenge 5: Use the KV v2 Secrets Engine
* In this lab, you'll enable and use the KV v2 secrets engine.
* Note that the path will be `kv` instead of `secret`.
* Instructions:
  * If the track does not do it for you, click the "Use the KV V2 Secrets Engine" challenge of the "Vault Basics" track.
  * Then click the green "Start" button.
  * Follow the challenge's instructions.
  * Click the green "Check" button when finished.

???
* Instruct the students to do the "Use the KV V2 Secrets Engine" challenge of the "Vault Basics" track.
* This challenge has them enable an instance of the KV v2 secrets engine.
* Emphasize that the path will be `kv` instead of `secret` as was the case for the challenges with the Dev mode server.

---
name: lab-vault-basics-challenge-6
# 👩‍💻 Challenge 6: Userpass Auth Method
* In this lab, you'll enable and use the Userpass auth method.
* Instructions:
  * If the track does not do it for you, click the "Use the Userpass Auth Method" challenge of the "Vault Basics" track.
  * Then click the green "Start" button.
  * Follow the challenge's instructions.
  * Click the green "Check" button when finished.

???
* Instruct the students to do the "Use the Userpass Auth Method" challenge of the "Vault Basics" track.
* This challenge has them enable an instance of the Userpass auth method.
* It also demonstrates that Vault is "deny by default" since the Userpass user that they create will not have any access to secrets yet.

---
name: lab-vault-basics-challenge-7
# 👩‍💻 Challenge 7: Vault Policies
* In this lab, you'll use Vault policies to grant different users access to different secrets.
* Instructions:
  * If the track does not do it for you, click the "Use Vault Policies" challenge of the "Vault Basics" track.
  * Then click the green "Start" button.
  * Follow the challenge's instructions.
  * Click the green "Check" button when finished.

???
* Instruct the students to do the "Use Vault Policies" challenge of the "Vault Basics" track.
* This challenge has them create a second user and create and associate policies with their 2 users.
* It then has them valdiate that each user can only access their own secrets.
