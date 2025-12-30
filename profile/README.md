<p align="center">
  <img src="/assets/banner.png" alt="XAuth Ecosystem Banner" width="900">
</p>

# XAuth Ecosystem Resources

Welcome to the official GitHub organization for **XAuth Ecosystem** — a comprehensive authentication and identity management solution for Minecraft: Bedrock Edition servers, evolving since 2021.

We develop and maintain an integrated suite of open-source plugins and tools that provide robust authentication, multi-platform account binding, and OAuth2-based identity federation for server owners and players.

---

## Core Projects

### Authentication & Security
- [**XAuth**](https://github.com/xauth-ecosystem/XAuth)  
  The foundation of our ecosystem — a modern, extensible authentication plugin for PocketMine-MP that controls user authorization flow with support for two-factor authentication and advanced security features.

- [**CaptchaLogin**](https://github.com/xauth-ecosystem/CaptchaLogin)  
  Adds an extra layer of verification using CAPTCHA challenges to prevent automated attacks and enhance account security.

### Account Binding & Integration
- [**BindingManager**](https://github.com/newlandpe/BindingManager)  
  Multi-platform account binding system. Started in 2021 with VKontakte integration via RCON, now supports Telegram and provides a flexible API for extending to other platforms.

- [**XAuthConnect**](https://github.com/xauth-ecosystem/XAuthConnect)  
  OAuth2 server with OpenID Connect implementation that runs directly on your game server. Enables server owners to connect custom platforms and services with player accounts through industry-standard authentication protocols.

### Supporting Tools & Libraries
- [**League OAuth2 Integration**](https://github.com/xauth-ecosystem/oauth2-xauthconnect)  
  Custom OAuth2 client library built on top of [thephpleague/oauth2-client](https://github.com/thephpleague/oauth2-client), designed specifically for integrating with XAuthConnect's OAuth2 server.

- [**Demo Client**](https://github.com/xauth-ecosystem/xauthconnect-php-demo-client)  
  Reference implementation showcasing how to integrate with XAuthConnect using the League library.

- [**Discord Role Bot**](https://github.com/xauth-ecosystem/discord-xauth-integration)  
  JavaScript-based Discord bot for automatic role assignment based on linked Minecraft accounts.

- [**NamelessMC Module**](https://github.com/xauth-ecosystem/namelessmc-xauthconnect-module)  
  Forum integration module that adds "Sign in with XAuthConnect" functionality to NamelessMC websites.

---

## Our Mission

- **Security First:** Protect player accounts through modern authentication standards and multi-factor verification
- **Seamless Integration:** Bridge Minecraft servers with external platforms via OAuth2 and custom bindings
- **Extensibility:** Provide flexible APIs and libraries for developers to build upon
- **Open Standards:** Implement industry-standard protocols like OAuth2 and OpenID Connect
- **Community-Driven:** Share tools and knowledge to empower server owners worldwide

---

## Architecture Overview

The XAuth Ecosystem consists of three layers:

1. **Core Authentication** — XAuth plugin manages player login and session security
2. **Enhanced Security** — CaptchaLogin and BindingManager add verification and platform linking
3. **Federation Layer** — XAuthConnect enables OAuth2/OpenID Connect for third-party integrations

This modular approach allows you to use components independently or combine them for comprehensive identity management.

---

## Getting Started

Each repository contains detailed installation instructions and documentation. For a typical setup:

1. Install **XAuth** as your base authentication system
2. Add **CaptchaLogin** or **BindingManager** for enhanced security
3. Deploy **XAuthConnect** if you need OAuth2 integration with external services

---

## Contributing

We welcome contributions from developers and server administrators!  
Whether it's code improvements, bug reports, documentation, or new integration ideas — your input helps the ecosystem grow.

Please explore our repositories, open issues, or submit pull requests.

---

## Support & Contact

For questions, feature requests, or technical support, please use GitHub Issues in the relevant repository or reach out through the contacts listed in each project.

---

*Building secure, connected experiences for Minecraft: Bedrock Edition since 2021.*
