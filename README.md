# Presentations
Repository of some of my presentations

## `unsafe` Cryptography: Common Vulnerabilities in Modern Programming Languages at ICMC 2024 in San Jose, CA 

In this talk, Paul will explore common vulnerabilities encountered in modern programming languages when implementing cryptographic systems. He will discuss prevalent security risks 
across languages like Rust, and how even languages designed with safety in mind can lead to subtle vulnerabilities. Whether you're new to cryptography or an experienced developer, 
this session will provide valuable insights to strengthen your understanding of secure coding practices in today's programming landscape.


* [Slides](2024_ICMC/ICMC24_Paul_Bottinelli_unsafe_cryptography.pdf)
* [Recording](https://youtu.be/tWglorc4aOo?si=pQvtbsyLoxJRpPAU&t=1758)

* Link to event: <https://icmconference.org/?session=cryptographic-technology-title-tba-g21b>


## Crypto Vulnerabilities in the Wild at Swiss Crypto Days 2023 in Zurich, Switzerland 

In this talk, Paul will present a few selected cryptography vulnerabilities identified through security reviews conducted by the Cryptography Services team at NCC Group. The presentation will start with an exploration of security flaws found in blockchain deployments, including a biased ChaCha20-based Random Number Generator due to erroneous programming language translation and an issue related to a missing parameter in the Fiat-Shamir computation of a Verifiable Random Function (VRF) leading to the break of its uniqueness property. The speaker will also discuss an ECDSA signature forgery arising from a missing step in the verification process, frequently affecting even modern threshold ECDSA implementations, as well as a TLS authentication bypass leveraging a poor state-machine design. This presentation will highlight the range of issues discovered during cryptography reviews and hopefully help cryptographers and developers avoid such errors.

* [Slides](2023_SwissCryptoDays/Paul%20Bottinelli%20-%20CryptoVulnsInTheWild%20-%20SCD23.pdf)
* Link to event: <https://swisscryptoday.github.io/2023/>


## Selected Cryptography Vulnerabilities of IoT Implementations at ICMC 2022 in Arlington, VA 

In this talk, Paul will present a number of selected cryptography vulnerabilities frequently encountered during security reviews and penetration tests of IoT solutions.

* [Slides](2022_ICMC/ICMC24_Paul_Bottinelli_unsafe_cryptography.pdf)
* Link to event: <https://icmconference.org/?session=selected-cryptography-vulnerabilities-of-iot-implementations-e32a>