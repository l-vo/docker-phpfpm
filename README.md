# Summary

This Dockerfile is based on the php-fpm 5.6 official image.

It removes the log flow from stdin/stdout (should be merged with the logs of a frontal Nginx) and set php display_errors flag to off.