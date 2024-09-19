# Ansible Role: Nginx Setup

## Overview

This Ansible role, `nginx_setup`, automates the installation and configuration of Nginx to serve static HTML pages. This document provides details about the Nginx setup within this role.

### Role Name

- **Role**: nginx_setup
- **Author**: Nishesh Thakuri
- **Description**: Automates the installation and configuration of Nginx for serving static web pages.

## Features

- Installs Nginx using the package manager.
- Creates the necessary directories for serving web content.
- Copies a customizable `index.html` file to the web root.
- Deploys a template-based Nginx configuration file.
- Ensures Nginx is enabled to start on boot.

## Requirements

- Ansible 2.9 or higher
- A compatible Linux distribution (e.g., Debian, Ubuntu)

## Supported Platforms

This role is compatible with the following platforms:

- **Debian**: All versions
- **Ubuntu**: All versions

## Role Variables

You can customize the following variables in your playbook or defaults:
