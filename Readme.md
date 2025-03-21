# AutomataVerse

AutomataVerse is an interactive educational platform for learning and experimenting with theory of computation concepts. The application provides intuitive visual simulators for various automata models that are fundamental to computer science.

![Automata-Verse Logo](public/logo.png)

## Features

### Interactive Simulators
- **Deterministic Finite Automaton (DFA)** - Visualize and simulate DFAs with step-by-step execution
- **Nondeterministic Finite Automaton (NFA)** - Experiment with multiple possible state transitions
- **Pushdown Automaton (PDA)** - Understand stack-based computation with visual stack representation
- **Turing Machine (TM)** - Explore the power of Turing Machines with multi-tape support and intuitive tape visualization
- **Finite State Machine (FSM)** - Moore and Mealy machines with output visualization

### Cloud Features
- **Cloud Save** - Save your automata designs securely to the cloud and access them from anywhere
- **Sharing** - Generate shareable links to your automata designs for easy collaboration
- **JSON Import/Export** - Load and save machines using JSON format for easy backup and migration

### Interactive Testing
- Test your machines with custom input strings 
- Watch state transitions in real-time with step-by-step visualization
- Visualize computation paths in all automata types

### User Profiles
- Create your personal profile to manage all your saved machines
- Track your learning progress
- Customize your learning experience

### Learning Resources
- Comprehensive tutorials on automata theory
- Interactive demonstrations with explanations
- Step-by-step guides for building and understanding different automata models

## Simulators in Detail

Automata-Verse provides a comprehensive suite of simulators covering the most important computational models in automata theory:

### Deterministic Finite Automaton (DFA)
The DFA simulator allows you to:
- Create and edit states with intuitive drag-and-drop interface
- Define transitions between states with labeled edges
- Set initial and accepting states
- Test input strings with step-by-step visualization
- See immediate validation of your automaton design
- Export and share your creations

### Nondeterministic Finite Automaton (NFA)
Our NFA simulator extends the DFA capabilities with:
- Support for epsilon (ε) transitions
- Visualization of multiple active states simultaneously
- Animation of parallel state transitions
- Step-by-step tracing of all possible computation paths
- Conversion between NFA and DFA representations

### Pushdown Automaton (PDA)
The PDA simulator includes:
- Visual stack representation that updates in real-time
- Support for stack operations (push, pop)
- Step-by-step animation of stack changes
- Clear visualization of how the stack influences state transitions
- Detailed breakdowns of computation steps

### Turing Machine (TM)
Our most powerful simulator offers:
- Multi-tape support for complex algorithms
- Intuitive visualization of tape contents
- Step-by-step execution with tape movement animation
- Support for user-defined transition functions
- Ability to create, save, and load complex Turing Machines
- Customizable tape alphabet and state set

Each simulator features a consistent user interface making it easy to transition between different computational models while learning the unique capabilities and constraints of each.

## Technologies Used

- **Frontend**: Next.js, React, TypeScript
- **State Management**: Redux
- **Authentication**: Firebase Authentication
- **Styling**: CSS Modules / Tailwind CSS
- **Visualization**: Custom-built graph visualization components
