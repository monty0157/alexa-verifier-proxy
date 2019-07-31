# Description

This module was forked from https://github.com/mreinstein/alexa-verifier. It has the same functionality, except for the fact that it uses the library request-promise to fetch the certificate from Amazon. This adds some more dependencies to the package, but it has the main benefit that request-promise is known to work well and out-of-the-box with proxies. As opposed to this fork of alexa-verifier: https://github.com/SahilDude89ss/alexa-verifier-with-proxy/blob/master/package.json, it works with the standard HTTP_PROXY and HTTPS_PROXY environment variables, causing less configuration overhead in e.g. a large microservice architecture.