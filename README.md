# Open AI API & MCP Sandbox
This is an API sandbox for the Open AI API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Open AI API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Open AI API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Open AI API & MCP Sandbox.

- Number of Paths: 33
- Number of Operations: 48
- Number of Read Operations: 19
- Number of Write Operations: 29
- Number of Schemas: 77
- Number of Responses: 0
- Number of Parameters: 0
- Number of Examples: 62
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Open AI API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Openai Assistants Api](openapi/assistants-openapi-original.yml)
  - [Openai Audio Api](openapi/audio-openapi-original.yml)
  - [Openai Chat Completions Api](openapi/chat-openapi-original.yml)
  - [Openai Completions Api](openapi/completions-openapi-original.yml)
  - [Openai Embeddings Api](openapi/embeddings-openapi-original.yml)
  - [Openai Files Api](openapi/files-openapi-original.yml)
  - [Openai Fine Tuning Api](openapi/fine-tuning-openapi-original.yml)
  - [Openai Images Api](openapi/images-openapi-original.yml)
  - [Openai Models Api](openapi/models-openapi-original.yml)
  - [Openai Threads Api](openapi/threads-openapi-original.yml)

## Resources
These are the resources available via the Open AI API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Assistant Files
  - Assistants
  - Chat Completions
  - Embeddings
  - File Content
  - File Management
  - Fine-tuning Events
  - Fine-tuning Jobs
  - Image Editing
  - Image Generation
  - Image Variations
  - Message Management
  - Model Discovery
  - Model Management
  - Run Execution
  - Run Steps
  - Speech To Text
  - Text Completions
  - Text To Speech
  - Thread Management

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Open AI API & MCP Sandbox.

  - Attach A File To An Assistant
  - Cancel Fine-tuning Job
  - Cancel Run
  - Create Fine-tuning Job
  - Create Image Variation
  - Create New Thread
  - Create Thread And Run
  - Create Thread Message
  - Create Thread Run
  - Create A Chat Completion
  - Create A Text Completion
  - Create An Assistant
  - Create Embeddings
  - Delete A File
  - Delete Fine-tuned Model
  - Delete Thread
  - Delete An Assistant
  - Delete An Assistant File
  - Download File Content
  - Edit Existing Image
  - Generate Image From Prompt
  - Generate Speech From Text
  - List All Files
  - List Available Models
  - List Fine-tuning Job Events
  - List Fine-tuning Jobs
  - List Run Steps
  - List Thread Messages
  - List Thread Runs
  - List All Assistants
  - List Assistant Files
  - Modify Message
  - Modify Run
  - Modify Thread
  - Modify An Assistant
  - Retrieve File Metadata
  - Retrieve Fine-tuning Job
  - Retrieve Message
  - Retrieve Model Details
  - Retrieve Run
  - Retrieve Run Step
  - Retrieve Thread
  - Retrieve An Assistant
  - Retrieve An Assistant File
  - Submit Tool Outputs
  - Transcribe Audio To Text
  - Translate Audio To English Text
  - Upload A File

## Backstage
We provide a Backstage software catalog entity for the Open AI API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Openai Assistants API](backstage/assistants-backstage-original.yml)
  - [Openai Audio API](backstage/audio-backstage-original.yml)
  - [Openai Chat Completions API](backstage/chat-backstage-original.yml)
  - [Openai Completions API](backstage/completions-backstage-original.yml)
  - [Openai Embeddings API](backstage/embeddings-backstage-original.yml)
  - [Openai Files API](backstage/files-backstage-original.yml)
  - [Openai Fine Tuning API](backstage/fine-tuning-backstage-original.yml)
  - [Openai Images API](backstage/images-backstage-original.yml)
  - [Openai Models API](backstage/models-backstage-original.yml)
  - [Openai Threads API](backstage/threads-backstage-original.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Open AI API & MCP Sandbox.

