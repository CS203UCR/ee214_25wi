This is the repo for EE214/PHYS220's in-class demos. To use the code in the repo, you need an environment that has qiskit installed. You may use the datahub.escalab.org service. 

If you want to use the datahub.escalab.org service, please follow these steps.

1. Navigate your browser to datahub.escalab.org and login with your UCR email
2. Choose the EE214 container.
3. Open a terminal in your environment
4. git clone git@github.com:CS203UCR/ee214_25wi.git
5. Navigate to the cloned repo.
6. git pull origin main
7. Enjoy the notebook!

You may need to create an ssh key and add it to your github account. You can create the key with (in your jupyterhub terminal):

```
ssh-keygen
```
and accept the defaults. I recommend no password, so you don't have to type it all the time.

Then view your new public key:
```
cat ~/.ssh/id_rsa.pub
```
Then follow these instructions:

https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

