Whilst automating our infrastructure, we needed to make sure that all nodes know of all certificates we use.

We've found [This great tutorial](http://www.opentox.org/tutorials/q-edit/how-to-install-ssl-certificates) on
how to make sure all Java applications trusts our certificates. The problem with the original InstallCert.zip
was that it had a manual step for accepting the certificates.

We've modified the code so that is no longer necessary, thus enabling this in our automation.
