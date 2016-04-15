# ASP.net tsuru platform

## Install

    $ git clone https://github.com/wagnersza/tsuru-aspnet.git
    $ cd tsuru-aspnet/aspnet-platform

    $ tsuru-admin platform-add aspnet -d .
      or
    $ tsuru-admin platform-add aspnet -i wagnersza/aspnet

## Deploy sample

    $ cd tsuru-aspnet/samples/HelloWeb
    $ tsuru app-deploy . -a < minha_app >
