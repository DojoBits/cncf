![CNCF Sofia Meetup](https://secure.meetupstatic.com/photos/event/9/8/2/7/clean_518858951.webp)

Hello and welcome to the CNCF Platform Engineering Meetup!

Here you'll find all of the materials that you'll need to complete the `CNCF OWASP Top 10 Kubernetes K01` workshop.


## Workshop Guides

In this repository you can find two files:

> Note: Please DON'T open the cncf-owasp-k8s-top-10-k01-solution.md till the end of the workshop!

- cncf-owasp-k8s-top-10-k01.md             - Workshop guide
- cncf-owasp-k8s-top-10-k01-solution.md    - Optional solution to the challenge tasks.


## Workshop VM

Each in-person attendee of the workshop will receive a physical paper with unique IP address. If you are joining us
remotely, we've provided instructions how you can build your own Kubernetes environment in a local VM.

## Accessing the Workshop VMs

To access your cloud based workshop vm you'll need:

- The IP address from the workshop sheet
- SSH key and client
- Username: `ubuntu`

The default unprivileged user that we'll use throughout the workshop is: `ubuntu`

Here is an example how to connect to your machine:

```shell
$ ssh -o IdentitiesOnly=yes -i ./keys-virginia/key.pem ubuntu@X.X.X.X
```

## SSH Keys

To access the Cloud VMs you'll need an SSH key for the authentication. Please follow those links to get the keys from S3
in either PEM or PPK format, depending on the SSH client that you use:

- PEM: bit.ly/3yJQ3Ry
- PPK: bit.ly/4bTDXnD


Enjoy!
