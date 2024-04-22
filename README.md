# PoK Growth Starter Template

Welcome to the Proof of Knowledge growth starter kit. This Obsidian vault has everything you need to start using PoK and, plug-and-play style, is ready to be used. Please, read the information below to understand how to set up the template (it's been mostly done for you now) and how to use it.

You can also check out [this video tutorial](https://share.cleanshot.com/S1WKk3fq) that shows you how to get started with this template.

## The Obsidian Interface And Basic Functionality

The Obsidian interface is divided into several parts. It may seem overwhelming at first, but it’s fairly straightforward to use:

- **File Explorer:** This is where you can view and navigate through all the notes in your vault. You can create new notes, delete existing ones, and organize notes into folders.
- **Edit and Preview Modes:** You can switch between edit mode (for writing or modifying a note) and preview mode (for viewing the note).
- **Backlinks Pane:** This pane shows you all the notes in your vault that link back to the current note. 
- **Graph View:** This feature visualizes all the notes in your vault and the connections between them.

To create new notes, simply click on the 'New note' icon on the file explorer. You can then start typing in the Edit mode. To make links between notes, you can leverage the double bracket `[[ ]]` syntax. For example, you can type `[[Note B]]` in Note A, to create a link from Note A to Note B.

## The Necessary Plugins

Plugins are a great way to extend the functionality of Obsidian and PoK uses them to make connections and use AI. That is why we have to make sure that the plugins are installed and enabled:

1. Open the Settings by clicking on the gear icon at the bottom of the left sidebar.
2. Navigate to the 'Community plugins' under 'Plugin options'.
3. Click 'Browse'.
4. You will now see a list of community plugins that you can search through, install, and enable.
    1. This template should already include the following plugins, which you will have to enable:
        1. Chat Stream:
        2. Smart Connections:
        3. Link Exploder
        4. MAKE.md
        5. Surfing

Remember to always verify the credibility and safety of the plugins before installing them, given that plugins often have deep access to Obsidian's functionality.

In the case of the Chat Stream and Smart Connections plugins, you will have to add your OpenAI API key to the settings (see the Using AI section below). To do that, you will find the settings page of each individual plugin on the left sidebar of the settings page. Click on Chat Stream and Smart Connections, and make sure you add your own API key in the corresponding field. Note that, while this template may have already included an API key, this may not be active.

## Using The PoK Growth Starter Template

The template is setup to keep the sidebar clean. There should only be a README file and three folders in it. At the moment, the idea is to use the template to work on a single PoK growth-related question, which you can find and edit to your current needs by opening the *Questions* folder.

All of your note-taking will happen through the Canvas. We have already created one for you with all the significant connections between study groups and topics made. These connections will help the AI be as precise as possible. You will see that all the study groups are connected to the question. This is their main connection point. Within each study group (box of notes), you will see notes about the different topics that correspond to the study group. When writing about an individual topic, you can write in its note directly from the Canvas or open it as a new tab. It is important to write "clean" notes, especially when importing content from the web, as this will ensure the AI performs better. Make sure you delete anything that doesn't add value to the point you're trying to make, like advertisements or sidebar content that websites often contain.

Remember that you can use the split-screen feature in Obsidian to browse the internet and create markdown notes from there by right-clicking. These notes will be created in the *Notes* folder and should be referenced from one of the notes in the canvas. To reference the note, use `![[]]` . This will expand the contents of the note you're referencing so it's visible from the canvas.

## Using AI

AI can bring a new angle to your research and help add a dimension of deep learning and predictive analysis to your engrams. "Chat Stream" is an Obsidian plugin for conversing with GPT AI via canvas notes. Ancestor notes/files are included in the chat context. You can quickly create chat streams, and control what other notes are sent to the AI.

*Setup: Add an [OpenAI API key](https://platform.openai.com/account/api-keys) in Chat Stream settings.

*Usage:

1. Select a note in the canvas
2. Press Alt+Shift+G to generate new note from GPT using current note + ancestors
3. To create next note for responding, press Alt+Shift+N.

AI notes are colored purple, and tagged with `chat_role=assistant` in the canvas data file.

Consider these points while designing AI execution for your engrams:

- **Flow Definition:** Define how the AI should read and understand your engram. This includes specifying the AI's entry point to the engram and the flow it should follow to read the data.
- **Interaction:** Engage the AI in dialogue, asking it questions based on the data and capturing the responses in your engram.
- **Monitoring AI Performance:** Watch how the AI interacts with your engrams and modifies its responses based on the data. Analyzing these insights can help improve your engram’s interactions with AI.

At the same time, you can use the chatbot on the right sidebar to ask questions about the complete graph of knowledge that you are building.

With time, practice, and a dedication to learning, the process of creating engrams will become second nature, enabling you to draw interesting insights from data, foster new ideas, and build intricate knowledge structures efficiently.

## Giving Feedback

If you have any feedback on how we could improve this starter template, please [open an issue on the GitHub repository](https://github.com/DeSciWorldDAO/DeSciWorld/issues/new/choose).