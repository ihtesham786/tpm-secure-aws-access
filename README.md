# TPM Secure AWS Access

Securely access AWS resources from non-AWS Linux instances using Trusted Platform Module (TPM) 2.0 and OpenSSL integration with AWS IAM Roles Anywhere.

## Overview

This project demonstrates how to leverage TPM 2.0 capabilities on Linux systems to enhance security when accessing AWS resources. By using TPM for key storage and AWS IAM Roles Anywhere for authentication, we eliminate the need for long-term credentials while providing robust protection against unauthorized access.

## Key Features

- Secure private key storage using TPM 2.0
- Integration with AWS IAM Roles Anywhere for temporary credential management
- Step-by-step guide for implementation on Linux systems
- Scripts and tools for automating the setup process

## Prerequisites

- Linux system with TPM 2.0 chip
- AWS account with IAM Roles Anywhere enabled
- OpenSSL with TPM provider support

## Quick Start

1. Clone this repository
2. Follow the setup instructions in `docs/setup-guide.md`
3. Run the provided scripts to configure your system

## Documentation

- [Setup Guide](docs/setup-guide.md)
- [TPM Key Management](docs/tpm-key-management.md)
- [AWS IAM Roles Anywhere Configuration](docs/aws-roles-anywhere-config.md)
- [Troubleshooting](docs/troubleshooting.md)

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
