# BME Thesis latex template
Latex thesis template for Budapest University of Technology and Economics.

It's based on the [Diplomaterv Portál](https://diplomaterv.vik.bme.hu/)'s template.

## Setup the GitHub Page

### 1. Generate an access token
First of all you need an access token. 
1. Visit the **Settings** of the user account
2. Under **Developer settings** you will find **Personal access tokens**, click on it.

3. Select the **Generate new token**
4. Fill the Token description (you can write whatever you want there) and **enable the repo scope** with the checkbox.
5. **Copy** the token

### 2. Add token as GitHub Secret
1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click **Settings**.
3. Repository settings button
4. In the left sidebar, click **Secrets**.
5. Click **Add a new secret**.
6. Type a name for your secret (**TOKEN**) in the **Name** input box.
7. **Paste** the value of the token for your secret.
8. Click **Add secret**.

### 3. Set up GitHub page in the repository

1. On GitHub, navigate to the main page of the repository.
2. Under your repository name, click **Settings**.
3. Scroll down to the **GitHub Pages** section
4. Select the `gh-pages` branch and the root  (/) directory.
5. Click **Save**.

> You need to rerun the GitHub Action to deploy the pdf.

## To build the PDF version of your thesis locally just run
```
make
```