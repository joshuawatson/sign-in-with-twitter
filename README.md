Sign in with Twitter
====================
Sign in with Twitter is a very basic Rails 3 application that demonstrates how
to use the [Sign in with Twitter][siwt] workflow using version 1.x of the
[twitter gem][twitter] (which has removed built-in OAuth support) and the
[omniauth gem][omniauth].

[siwt]: http://dev.twitter.com/pages/sign_in_with_twitter
[twitter]: https://github.com/jnunemaker/twitter
[omniauth]: https://github.com/intridea/omniauth

Installation
------------
    git clone git://github.com/sferik/sign-in-with-twitter.git
    cd sign-in-with-twitter
    bundle install

Usage
-----
Sign in with Twitter requires you to [register an app with Twitter][apps] to
obtain OAuth credentials. Once you obtain credentials, substitute your consumer
key and secret into the command below.

[apps]: http://dev.twitter.com/apps

    CONSUMER_KEY=abc CONSUMER_SECRET=123 rails server
