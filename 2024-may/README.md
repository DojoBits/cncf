![CNCF Sofia Meetup](https://secure.meetupstatic.com/photos/event/9/8/2/7/clean_518858951.webp)

Hello and welcome to the CNCF Platform Engineering Meetup!

Here are all of the materials you need to complete the CNCF OWASP Top 10 Kubernetes K01 workshop.


> Disclaimer: The resource references will *only* be valid for the duration of the event!


## Workshop Guides

In this repository, you can find two files:

> Note: Please DON'T open the cncf-owasp-k8s-top-10-k01-solution.md till the end of the workshop!

- cncf-owasp-k8s-top-10-k01.md             - Workshop guide
- cncf-owasp-k8s-top-10-k01-solution.md    - Optional solution to the challenge tasks.


## Workshop VM

Each in-person attendee of the workshop will receive a physical paper with a unique IP address. If you are joining us
remotely, we've provided instructions on how you can build your own Kubernetes environment in a local VM.

## Accessing the Workshop VMs

To access your cloud-based workshop Virtual Machine, you'll need:

- The IP address from the workshop sheet
- SSH key and client
- Username: `ubuntu`

The default unprivileged user that we'll use throughout the workshop is: `ubuntu`

Here is an example of how to connect to your machine:

```shell
$ ssh -o IdentitiesOnly=yes -i ./keys-virginia/key.pem ubuntu@X.X.X.X
```

## SSH Keys

To access the Cloud VMs, you'll need an SSH key to authenticate. Please follow those links to get the keys from S3
in either PEM or PPK format, depending on the SSH client that you use:

- [PEM]()
- [PPK]()


Enjoy!
