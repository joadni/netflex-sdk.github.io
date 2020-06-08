# Netflex SDK

Documentation for the Netflex SDK version 2.0.

## What is Netflex SDK?
The [Netflex SDK](https://github.com/netflex-sdk) is a collection of libraries that enables you to work with the [Netflex API](https://documenter.getpostman.com/view/1198765/7159G1N?version=latest).

It superseeds the legacy Netflex SDK v1.3.x.

## Legacy
v1.3.x will be supported for the forseeable future, but will only receive compatibility and security patches. If feasible, you should consider upgrading your legacy project. See the [migration guide](/docs/migration-guide.md).

## Purpose
The Netflex SDK is built on top of the excellent PHP framework, [Laravel](http://laravel.com) version 7. This enables you to leverage much of the existing documentation and tools built around the Laravel ecosystem.

Most Netflex sites are just a regular Laravel 7 application, with Netflex SDK packages and some custom configuration.

The purpose of this document, is to outline where the Netflex SDK and Laravel diverges in behavior and implementation.

When possible, please first refer to [Laravels documentation](https://laravel.com/docs/7.x), and use this documentation as an appendix for that document.