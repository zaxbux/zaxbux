## ⚡️ I'm excited about these projects ...

### OpenSprinkler

OpenSprinkler is a an open-source project that consists of hardware, controller software, a web app, and a weather service. I purchased a set of assembled controller PCBs (Raspberry Pi version) from their online store for my family's property.

#### Controller Firmware

While the existing software implementation is effective, I saw room for improvement and decided to rewrite the controller software. I chose the Rust programming language for it's package ecosystem, memory safety features, and relative ease of porting from C++ code. I have never used Rust prior to this project.

Summary of enhancements:

* Security: Better support of TLS. Login uses modern hash algorithms (Argon2) instead of MD5. Multiple user support (relies on weather service).
* Connectivity: IPv6 support. Simplified configuration API. Remote configuration (relies on weather service).
* Stability: Implementing unit tests.

#### Web App

Configuratio of the controller stations and irrigation schedules is done through a web-based application. I sought to improve some parts of the app and decided to create my own version using TypeScript and Vue 3. Since I am making significant chnages to the controller software, this allows me to add new features.

#### Weather Service

I also modified the weather service to be compatible with Cloudflare Workers, a serverless web platform. The weather service responds to geocoding requests from the controller to determine it's geographic coordinates, timezone, and other data. The controller also requests weather data to determine if irrigation is necessary and how much water should be used. 

## 🔭 I'm currently working on ...

 * A rust implimentation of OpenSprinkler
 * Winter CMS plugins
 * Backblaze B2 API libraries

## 🌱 I'm currently learning ...

 * Rust
 * Vue
 * TypeScript
 * Unit testing

<!-- ## 👯 I'm looking to collaborate on ... -->

<!-- ## 🤔 I'm looking for help with ... -->

<!-- ## 💬 Ask me about ... -->

## 📫 How to reach me:

 * [Email](hello@zacharyschneider.ca)
 * <a rel="me" href="https://mstdn.ca/@zach_s">Mastodon</a>

## 😄 Pronouns:

 * he/him

## ⚡ Fun fact: ...

 * I've been programming for almost a decade.
