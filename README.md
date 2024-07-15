# AI code-generation software: What it is and how it works

Using generative artificial intelligence (AI) solutions to produce computer code helps streamline the software development process and makes it easier for developers of all skill levels to write code. The user enters a text prompt describing what the code should do, and the generative AI code development tool automatically creates the code. It can also modernize legacy code and translate code from one programming language to another.

By infusing artificial intelligence into the developer toolkit, these solutions can produce high-quality code recommendations based on the user’s input. Auto-generated code suggestions can increase developers’ productivity and optimize their workflow by providing straightforward answers, handling routine coding tasks, reducing the need to context switch and conserving mental energy. It can also help identify coding errors and potential security vulnerabilities.

## How does generative AI code generation work?

Generative AI for coding is possible because of recent breakthroughs in large language model (LLM) technologies and natural language processing (NLP). It uses deep learning algorithms and large neural networks trained on vast datasets of diverse existing source code. Training code generally comes from publicly available code produced by open-source projects.

Programmers enter plain text prompts describing what they want the code to do. Generative AI tools suggest code snippets or full functions, streamlining the coding process by handling repetitive tasks and reducing manual coding. Generative AI can also translate code from one language to another, streamlining code conversion or modernization projects, such as updating legacy applications by transforming COBOL to Java.

Even as code produced by generative AI and LLM technologies becomes more accurate, it can still contain flaws and should be reviewed, edited and refined by people. Some generative AI for code tools automatically create unit tests to help with this.

## What are the benefits of using generative AI for code?

Using AI code generation software is generally straightforward and available for many programming languages and frameworks, and it’s accessible to both developers and non-developers.

There are three main benefits of using AI code-generation software tools:

It saves time by enabling developers to generate code faster, reducing the work of manually writing lines of code and freeing developers to focus on higher-value work.
Generative AI can quickly and efficiently test and debug computer code.
Using generative AI for code also makes code development accessible to non-developers.

## How does generative AI for code differ from low- and no-code?

Generative AI, low-code and no-code all provide ways to generate code quickly. However, low-code and no-code tools depend on prebuilt templates and libraries of components. The tools enable people without coding skills to use visual interfaces and intuitive controls like drag-and-drop to create and modify applications quickly and efficiently while the actual code remains hidden in the background.
Generative AI for code software, on the other hand, doesn’t use templates and libraries of components. The software reads a developer’s plain language prompts and suggests code snippets from scratch that will produce the desired results.

While low-code and no-code tools generally target non-developers and business users, both professional developers and other users can use AI code-generation software.

## Examples of currently available generative AI code generation tools

* Team4 Code Whisperer: TCW is an AI code assistant that learns from the codebase being worked on and provides real-time code completion, chat and code generation. It includes code formatting, language detection and documentation. Team4 Code Whisperer supports Java and JavaScript, and it integrates into VSCode.
* IBM watsonx Code Assistant: IBM watsonx Code Assistant helps developers write code using AI-generated recommendations, no matter their experience level. Developers can make requests in plain language or use existing source code to generate code for targeted use cases. Out-of-the-box, watsonx Code Assistant provides pre-trained models based on specific programming languages to ensure trust and efficiency for accurate code generation.
* Github Copilot: Github Copilot is a pre-trained AI model and code completion tool that writes code in many languages, including JavaScript, Go, Perl, PHP, Ruby, Swift and TypeScript, and works with HTML and CSS. It uses machine learning to suggest code based on context, can analyze your code for vulnerabilities and is available as an extension for integrated development environments (IDEs) like Visual Studio Code, Visual Studio, Neovim and JetBrains. GitHub Copilot uses publicly available code from GitHub repositories and is powered by OpenAI Codex, based on GPT-3.

## Installation of Team4 Code Whisperer (TCW)

The Team4 Code Whisperer works as an extension to Visual Studio Code.

### Extension for Microsoft VisualStudio Code

[Download the Visual Studio Code extension](https://github.com/nad-ang) | Updated 04 July 2024, 941 MB

#### To install the extension:
1. In Visual Studio Code, click the Extensions icon  to open the panel.
2. In the Extensions panel, click the three-dot Views and More Actions icon, then click Install from VSIX.
3. Select the VSIX file that you downloaded.
#### To open Team4 Code Whisperer for Enterprise Java Applications:
1. Click the Team4 Code Whisperer for Enterprise Java Applications icon  to open the panel.
2. Click Enter API key.
3. Enter your API key, then press Enter.
Note: You create an API key as part of the Team4 Code Whisperer setup in IBM Cloud. For more information, see instructions for creating an API key.
#### To uninstall the extension
1. In Visual Studio Code, click the Extensions icon to open the panel.
2. Click the Team4 Code Whisperer for Enterprise Java Applications extension, then click Uninstall.

## What can I do in watsonx Code Assistant for Enterprise Java Applications?
* Generate Java code.
* Explain Java code.
* Generate JUnit tests.
* Modernize your runtime.
* Upgrade your Java code based on changes that watsonx Code Assistant for Enterprise Java Applications identifies.

## On what operating systems and hardware architectures is the IDE client supported?
The Visual Studio Code IDE extension support the following operating systems and hardware architectures:
* Windows on the Intel X86 architecture
* MacOS on the Intel X86 architecture
* MacOS on the ARM architecture
Microsoft, Windows, Windows NT, and the Windows logo are trademarks of Microsoft Corporation in the United States, other countries, or both.

## What are the minimum software requirements for the extension?
* GitHub, for application differentiation summaries.
* Java SE 11 with JDK 11, or a later version.
* Maven. Only Maven build configurations are supported.
The JDK and Maven must be installed, and available to the system on the global path.

## What is the model for Team4 Code Whisperer for Enterprise Java Applications and what are the data sources to train the model?
The model used is the IBM Granite 20B enterprise Java code instruct model. This model was trained in two phases. In the first phase, the model was trained on 3 to 4 trillion tokens sourced from 116 programming languages, ensuring a comprehensive understanding of programming languages and syntax. In the second phase, the model was additionally trained on 500 billion tokens with a carefully designed mixture of high-quality data from code and natural language domains to improve the model's ability to reason. For more information about the IBM Granite 20B enterprise Java code instruct model, see Granite Code Models: A Family of Open Foundation Models for Code Intelligence.

Training of the IBM Granite 20B enterprise Java code instruct model included datasets for Jakarta EE, MicroProfile, and other enterprise Java repositories such as Open Liberty GitHub repositories.

## What level of code explanation do you provide?
Generative AI provides various explanations, including the following ones:
* Code recommendation, generation, explanation
* Summarization of code changes after upgrades
* Configuration generation, API recommendations, and runtime insight

