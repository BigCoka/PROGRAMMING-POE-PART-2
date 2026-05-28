# PROGRAMMING-POE-PART-2

Cryptonix CyberSecurity AI ChatBot

Cryptonix is an interactive desktop application built using Windows Presentation Foundation (WPF) and C#. Designed as an educational assistant, the application greets users via custom voice output, captures and stores localized profiling interests into permanent storage files, and deploys an automated semantic parsing loop to answers critical user questions regarding modern cybersecurity threats.

Key Features

Dynamic UI Layout Transitions: Uses single-window multi-grid container filtering logic ('home_grid', 'username_grid', and 'chat_grid') to manage state navigation instantly without launching multiple operating system window boundaries.
Immersive Audio Engine Architecture: Integrates native 'System.Media.SoundPlayer' resources to deliver real-time personalized acoustic welcome greetings at app launch initialization.
Persistent Interest Profiles: Interacts with physical local system data pipelines ('interested_topic.txt') using high-performance 'System.IO' streaming writers to store, update, append, and filter unique customer interest profiles without duplicate text bloating.
Keyword Prefix Parsing Engine: Deploys an array parsing routine that strips custom data payload tags via character string splits, mapping raw user sentences against predefined advice arrays.
Elastic UI Component Structure: Styled utilizing dynamic WPF grid layouts ('RowDefinitions' and 'ColumnDefinitions') ensuring user-friendly application scalability across high-density monitor screens.


Code Architecture Mapping

The system workspace structure relies on distinct decoupled class structures:
MainWindow.xaml/MainWindow.xaml.cs: Coordinates core framework view logic layout updates, cleans incoming text fields, manages tracking loops, and loads list components into active window rendering panels.
respond.cs: Houses the foundational knowledge arrays (reply / ignore) and processes user input text fragments against keyword indices.
voice_greeting.cs: Resolves deployment file path calculations using programmatic reflection methods to discover, play, and isolate the binary sound file track safely.
user_name.cs: Manages identification data layers and runtime validation checks before granting interface dashboard permissions.

Project Setup & Installation

Prerequisites
1. Microsoft Visual Studio
2. .NET Desktop Development Workload Package
3. WPF Native Core Execution Environment Runtime

Step-by-Step Installation

1. Open the solution inside Visual Studio.
2. Ensure your custom audio track 'greeting.wav' and image banner 'CRYPTONIX.jpg' are copied inside your primary system root folder directory (parallel to the .csproj solution location).
3. Select the 'greeting.wav' track asset from your Solution Explorer.
4. In the Properties Panel, toggle `Copy to Output Directory` to "Copy if newer".
5. Press 'F5' or select 'Start Debugging' from the compiler operations bar to run the operational builds.
