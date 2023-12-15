# VaultCord verification page

> [!NOTE]  
> You don't need to use GitHub anymore for VaultCord. You can choose the **Automatic** option on the dashboard to skip needing a GitHub account. GitHub simply gives you more customization over the design and text shown.

This is a verification page for the Discord backup bot [VaultCord](https://vaultcord.com) which can backup Discord members, Discord server channels, roles, messages, etc!

![image](https://github.com/VaultCord/vaultcord.github.io/assets/83034852/7b8e8771-149d-48ec-a89f-94dfa139cded)

Click the **Use this template** button. Do <ins>**NOT**</ins> fork this repository. That will link your server to VaultCord which isn't good for privacy among other reasons.

Name your repository `your_username.github.io` so that it works correctly.

![image](https://github.com/VaultCord/vaultcord.github.io/assets/83034852/e4071e0d-12ba-4c41-b212-a83810d34e87)
![image](https://github.com/VaultCord/vaultcord.github.io/assets/83034852/56ea530e-47ef-45fc-ac76-8efde04f64bf)

Click the top right avatar on GitHub to see your username. Mine is `wnelson03`, so I will set my repository name to `wnelson03.github.io`. Follow the same process to choose your repository name.

If you followed this correctly, you will be able to go to the `.github.io` domain and it will have the verification page. You may need to wait a minute or two for GitHub to process the new repository.

If you want your own custom domain such as `verify.mysite.com`, follow [these instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

### Verified message

You can customize the verified message by changing the value for `vc-verify-success` in the `index.html` file.

```html
vc-verify-success="You are verified now!"
```

### Error message

You can customize the error message by changing the value for `vc-verify-error` in the `index.html` file.

```html
vc-verify-error=="We have detected an error!"
```

### Captcha message

You can customize the captcha message by changing the value for `vc-captcha-require` in the `index.html` file.

```html
vc-captcha-require="We require a captcha to check you are human!"
```
