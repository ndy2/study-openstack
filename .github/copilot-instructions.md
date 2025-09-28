# Copilot Instructions for OpenStack Study Project

## Project Overview
This is a comprehensive study project focused on learning OpenStack, an open-source cloud computing platform. The project follows the Udemy OpenStack Essentials course and includes hands-on practice with OpenStack components, architecture, and operations.

## Key Learning Areas
- Cloud computing fundamentals
- OpenStack architecture and core components
- OpenStack networking (Neutron)
- Storage solutions (Swift for object storage, Cinder for block storage)
- Instance lifecycle management (Nova)
- Dashboard operations (Horizon)
- Command-line interface (CLI) operations
- Installation and deployment procedures

## Project Structure Guidelines

### Documentation Organization
- Each section should have its own README.md with detailed notes
- Use clear headings and subheadings for topics
- Include practical examples and commands
- Add screenshots and diagrams in `images/` folders within each section
- Follow consistent naming conventions for files and folders

### Content Standards
- Write explanations in a clear, educational manner
- Include both theoretical concepts and practical applications
- Document CLI commands with proper syntax and examples
- Explain configuration files and their purposes
- Note common issues and troubleshooting steps

## Code and Configuration Guidelines

### OpenStack Configuration Files
- Use YAML format for configuration examples
- Include comments explaining each configuration parameter
- Provide both minimal and comprehensive configuration examples
- Document environment-specific variables clearly

### CLI Commands
- Always include the full command syntax
- Provide examples with actual parameters
- Explain what each flag/option does
- Show expected output when helpful
- Group related commands together

## Writing Style
- Use present tense for explanations
- Write in an instructional, tutorial-like manner
- Include "why" explanations, not just "how"
- Reference official OpenStack documentation when appropriate
- Use bullet points and numbered lists for clarity

## Technical Focus Areas

### Core Components to Cover
- **Nova** (Compute): Instance management, flavors, images
- **Neutron** (Networking): Networks, subnets, routers, security groups
- **Cinder** (Block Storage): Volumes, snapshots, backups
- **Swift** (Object Storage): Containers, objects, metadata
- **Glance** (Image Service): Image management and formats
- **Keystone** (Identity): Users, projects, roles, authentication
- **Horizon** (Dashboard): Web interface operations

### Installation and Deployment
- DevStack for development environments
- Production deployment considerations
- Multi-node vs single-node setups
- Containerized deployments

## File Naming Conventions
- Use lowercase with hyphens for directories: `section-01-introduction`
- Use descriptive names for markdown files: `networking-concepts.md`
- Prefix exercise files with numbers: `01-create-instance.md`
- Use consistent image naming: `YYYY-MM-DD-HH-MM-SS.png`

## Content Creation Assistance
When helping with this project:
1. Always consider the educational nature of the content
2. Provide both beginner-friendly explanations and advanced details
3. Include practical examples that can be tested
4. Reference official OpenStack documentation
5. Suggest best practices for production environments
6. Help maintain consistency across all sections

## Common Commands and Tools
- `openstack` CLI client
- `nova`, `neutron`, `cinder` legacy clients
- Configuration management tools
- Debugging and logging commands
- Performance monitoring tools

This project aims to build comprehensive knowledge of OpenStack from fundamentals to advanced operations, suitable for both learning and future reference.
