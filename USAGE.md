# Usage Guide 📖

Complete guide to using the RAG Architecture Explorer effectively.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Interface Overview](#interface-overview)
3. [Exploring Architectures](#exploring-architectures)
4. [Using Scenarios](#using-scenarios)
5. [Understanding Metrics](#understanding-metrics)
6. [Advanced Features](#advanced-features)
7. [Tips & Tricks](#tips--tricks)

---

## Getting Started

### Opening the Tool
Simply open `index.html` in your web browser. No installation or setup required!

**Recommended browsers:**
- Chrome/Edge 90+ (best performance)
- Firefox 88+
- Safari 14+

### First Look
When you open the tool, you'll see:
- **Header** - Architecture selector buttons
- **Canvas** - Visual representation with animated particles
- **Info Panel** (left) - Details about selected components
- **Metrics Panel** (right) - Performance comparison

---

## Interface Overview

### Header Controls

#### Architecture Buttons
Eight buttons representing different RAG patterns:
- **🎯 Naive** - Simplest approach
- **🎨 Multimodal** - Multi-format processing
- **💡 HyDE** - Hypothetical embeddings
- **✅ Corrective** - Self-correcting
- **🕸️ Graph** - Knowledge graph-based
- **🔀 Hybrid** - Combined approach
- **🎯 Adaptive** - Smart routing
- **🤖 Agentic** - Multi-agent system

#### Scenario Presets
Quick-jump to recommended architectures:
- **🙋 Customer Support** → Corrective RAG
- **🔬 Deep Research** → Graph RAG
- **🎨 Creative Vision** → Multimodal RAG

### Canvas Area

The main visualization shows:
- **Nodes** - Components in the architecture (circles)
- **Edges** - Data flow connections (lines)
- **Particles** - Animated dots showing active data flow

**Node Colors:**
- 🔵 **Blue** - Input components (queries, data)
- 🟣 **Purple** - Processing (embedding, analysis)
- 🟠 **Orange** - Storage (databases)
- 🟢 **Green** - Generation/Output (LLMs, responses)

### Info Panel (Left Side)

Shows two types of information:

**When no node is selected:**
- Architecture overview
- Purpose and use cases
- Key focus points

**When a node is clicked:**
- Component name and description
- Technical details
- Performance metrics (if available)
- Examples and use cases

### Metrics Panel (Top Right)

Real-time performance comparison:
- **⚡ Latency** - How fast it responds
  - Fast: <100ms typical
  - Medium: 100-500ms
  - Slow: >500ms
- **💰 Cost** - Operational expenses
  - Low: Basic embedding + simple retrieval
  - Medium: Multiple models or complex processing
  - High: Multiple LLM calls, large-scale storage
- **✅ Reliability** - How dependable the output is
  - Moderate: May miss context occasionally
  - High: Generally accurate with good retrieval
  - Very High: Self-correcting or multi-validated

---

## Exploring Architectures

### Viewing an Architecture

1. **Click an architecture button** in the header
2. The canvas updates to show that architecture's flow
3. Watch particles animate the data flow
4. Read the overview in the info panel

### Understanding the Flow

Follow the particle animation:
1. Particles start at **input nodes** (usually blue)
2. Flow through **processing nodes** (purple)
3. Access **storage nodes** (orange) for retrieval
4. Generate output via **LLM nodes** (green)
5. Return final **response** to user

### Comparing Architectures

To compare different approaches:
1. Select first architecture (e.g., Naive RAG)
2. Note the simplicity and components
3. Check metrics (Fast, Low cost, Moderate reliability)
4. Switch to another (e.g., Corrective RAG)
5. Observe additional components (Relevance Grader, Web Search)
6. Compare metrics (Medium speed, Medium cost, High reliability)

---

## Using Scenarios

Scenarios help you find the right architecture for specific use cases.

### Customer Support 🙋

**Click the button to see:**
- Switches to **Corrective RAG**
- Explanation of why this fits customer support
- Focus on self-correction and web fallback

**Why Corrective RAG for support?**
- Grades internal knowledge base responses
- Falls back to web search when needed
- Ensures accurate, up-to-date answers
- Handles "I don't know" gracefully

### Deep Research 🔬

**Click the button to see:**
- Switches to **Graph RAG**
- Explanation of relationship mapping
- Focus on multi-hop reasoning

**Why Graph RAG for research?**
- Maps entities and relationships
- Enables complex queries across connections
- Discovers non-obvious links
- Better for dense, interconnected knowledge

### Creative Vision 🎨

**Click the button to see:**
- Switches to **Multimodal RAG**
- Explanation of multi-format processing
- Focus on visual and audio integration

**Why Multimodal RAG for creative work?**
- Processes images, video, audio, text together
- Understands visual context
- Generates rich, format-aware responses
- Perfect for media and design workflows

---

## Understanding Metrics

### Latency ⚡

**What it measures:** Response time from query to answer

**Fast (Naive, Multimodal):**
- Single retrieval pass
- Minimal processing overhead
- Best for: Real-time chat, instant answers

**Medium (Corrective, HyDE, Adaptive):**
- Multiple steps or verification
- Some additional processing
- Best for: Quality-focused applications

**Slow (Graph, Agentic):**
- Complex multi-hop reasoning
- Agent coordination overhead
- Best for: Deep analysis, research

### Cost 💰

**What it measures:** Operational expenses per query

**Low (Naive):**
- Single embedding
- Simple vector search
- One LLM call
- Best for: High-volume, budget-conscious apps

**Medium (Multimodal, Corrective, HyDE, Hybrid):**
- Multiple embeddings or searches
- Some redundant operations
- Best for: Production applications

**High (Graph, Adaptive, Agentic):**
- Multiple LLM calls
- Complex processing
- Agent coordination
- Best for: High-value queries

### Reliability ✅

**What it measures:** Consistency and accuracy of responses

**Moderate (Naive):**
- Depends on retrieval quality
- No verification steps
- Best for: Non-critical information

**High (Most architectures):**
- Better retrieval strategies
- Some quality control
- Best for: Business applications

**Very High (Corrective, Agentic):**
- Self-correction mechanisms
- Multi-agent verification
- Web fallback for missing info
- Best for: Critical applications

---

## Advanced Features

### Path Tracing

**How to use:**
1. Click any node in the architecture
2. Watch edges light up showing:
   - **Upstream path** - How data reaches this node
   - **Downstream path** - Where data goes from here
3. Animated glow pulses along active edges

**What it shows:**
- Complete data lineage
- Dependencies between components
- Critical path through the system

**Use cases:**
- Understanding bottlenecks
- Debugging data flow issues
- Explaining architecture to stakeholders

### Node Details

**Click any node to see:**
- **Description** - What it does
- **Purpose** - Why it exists
- **Details** - Technical specifics
  - Models used
  - Processing steps
  - Configuration options
- **Examples** - Real-world usage

**Useful for:**
- Learning specific components
- Comparing implementations
- Technical documentation

---

## Tips & Tricks

### Learning Strategy

**For Beginners:**
1. Start with Naive RAG (simplest)
2. Understand the basic flow
3. Progress to Multimodal or HyDE
4. Compare differences in components

**For Experienced Users:**
1. Use scenarios to find optimal architecture
2. Compare metrics for your use case
3. Trace paths to understand bottlenecks
4. Evaluate tradeoffs between architectures

### Making Decisions

**Choosing the right architecture:**

1. **Define requirements:**
   - Response time needs?
   - Budget constraints?
   - Accuracy requirements?
   - Data types (text, images, etc.)?

2. **Check scenarios:**
   - Does your use case match a preset?
   - If yes, start with that recommendation

3. **Compare metrics:**
   - Can you tolerate higher latency for better accuracy?
   - Is cost a major constraint?
   - How critical is reliability?

4. **Evaluate complexity:**
   - Do you have engineering resources?
   - How much maintenance can you handle?
   - What's your deployment timeline?

### Common Patterns

**High-volume, cost-sensitive → Naive RAG**
- Simple, fast, cheap
- Good for FAQs, basic search

**Accuracy-critical → Corrective RAG**
- Self-corrects mistakes
- Web fallback for currency
- Good for customer support

**Complex reasoning → Graph RAG**
- Multi-hop queries
- Relationship discovery
- Good for research, investigation

**Mixed media → Multimodal RAG**
- Images, video, audio
- Rich context understanding
- Good for e-commerce, media

**Unknown query types → Adaptive RAG**
- Routes automatically
- Optimizes per query
- Good for production systems

---

## Keyboard Shortcuts

Currently, all interactions are mouse/touch-based. Keyboard shortcuts are planned for v2.1.0!

**Planned:**
- `1-8` - Switch architectures
- `Space` - Play/pause particle animation
- `R` - Reset view
- `?` - Show help

---

## Troubleshooting

### Particles not animating
- Check browser compatibility
- Try refreshing the page
- Ensure hardware acceleration is enabled

### Info panel not updating
- Make sure you're clicking directly on nodes
- Try clicking different nodes
- Refresh if issue persists

### Mobile layout issues
- Rotate to landscape for better view
- Use pinch-to-zoom if needed
- Some features work best on desktop

---

## Need More Help?

- **Check the README** - Overview and quick start
- **Read CONTRIBUTING.md** - Technical details and code structure
- **Open an issue** - Report bugs or ask questions
- **Start a discussion** - Get help from the community

---

**Happy exploring!** 🚀
