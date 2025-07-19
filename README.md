# 🚀 Gemini Blog Machine

An intelligent, AI-powered blog creation system that guides you through a structured workflow to produce high-quality, SEO-optimized blog posts. Built with flexibility in mind - start simple and add advanced features as needed.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Quick Start](#quick-start)
- [Installation](#installation)
- [How It Works](#how-it-works)
- [Workflow](#workflow)
- [Advanced Features](#advanced-features)
- [Example Outputs](#example-outputs)
- [Use Cases](#use-cases)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Gemini Blog Machine is an AI assistant that helps you create professional blog posts through an interactive, conversational workflow. It combines best practices in content creation, SEO optimization, and technical writing to produce engaging, well-structured content.

### Key Benefits:
- **Structured Approach**: Follows a proven workflow from ideation to publication
- **SEO-Optimized**: Built-in SEO research and optimization
- **Flexible**: Core features by default, advanced options on demand
- **Quality Control**: Automated review and improvement suggestions
- **Style Consistency**: Maintains your chosen writing style throughout

## ✨ Features

### Core Features (Default)
- Interactive discussion to understand your blog requirements
- Basic SEO research and keyword optimization
- Structured content planning with hooks and clear problem statements
- Style configuration for consistent tone and voice
- Automated review with improvement suggestions
- Support for code tutorials with flexible formatting options

### Optional Advanced Features
- **Deep SEO Analysis**: Competitor analysis, content gaps, featured snippets
- **Content Intelligence**: Detailed content briefs with word counts and subtopics
- **Visual Planning**: Image and diagram placement markers
- **Persona Development**: Detailed audience personas for targeted content
- **AI-Enhanced Review**: Fact-checking, plagiarism detection, tone consistency
- **Multi-format Support**: Tutorials, how-tos, listicles, case studies

## 🚀 Quick Start

1. Place the `GEMINI.md` file in your blog project folder
2. Run your AI assistant in this folder
3. The assistant will greet you: "Hello! What do you want to blog about today?"
4. Answer the questions conversationally
5. Say "Proceed to reference" when ready to move forward
6. Say "Proceed to style" to generate style configuration
7. Say "Proceed to blog" to create your blog post
8. Say "Review blog" for automated quality checks

## 📦 Installation

### Prerequisites
- An AI assistant that can read and follow the GEMINI.md instructions
- File system access for creating and editing files
- (Optional) Web search capabilities for SEO research

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/blog-machine.git
   cd blog-machine
   ```

2. Ensure your AI assistant has access to:
   - File read/write permissions
   - Web search (optional but recommended)
   - The GEMINI.md guidelines file

3. Create a working directory for your blog:
   ```bash
   mkdir my-blog
   cp GEMINI.md my-blog/
   cd my-blog
   ```

## 🔄 How It Works

The Gemini Blog Machine follows a structured workflow with checkpoints at each stage:

```
Discussion → SEO Check → Reference → Style → Generate → Review → Publish
```

### Core Components

1. **GEMINI.md**: The instruction set that guides the AI assistant
2. **style.json**: Configuration file defining your blog's characteristics
3. **review.json**: Automated review criteria and checkpoints
4. **[slug].md**: Your generated blog post

### Optional Components
- **brief.json**: Detailed content planning document
- **seo-research.json**: Comprehensive SEO analysis
- **personas.json**: Detailed audience persona definitions

## 📝 Workflow

### 1. Discussion Phase
The assistant asks about:
- Main topic or idea
- Target audience
- Preferred style and tone
- Content structure and key points
- SEO keywords
- Code examples (for tutorials)

### 2. Quick SEO Check
Automatic basic search to:
- Identify top-ranking content
- Find common questions
- Suggest improvements

### 3. Reference Phase
- Checks for `reference.md` file
- Uses it for fact-checking only (not content copying)
- Can search web for additional information

### 4. Style Configuration
Creates `style.json` with:
```json
{
  "blogTitle": "Your Blog Title",
  "audience": "beginners",
  "tone": "conversational",
  "structure": {
    "hookType": "question",
    "sections": [...]
  }
}
```

### 5. Blog Generation
- Creates original content based on style guidelines
- Adds visual placeholders
- Formats code blocks (if applicable)
- Maintains consistent voice

### 6. Review Phase
- Automated quality checks
- SEO optimization verification
- Readability assessment
- Improvement suggestions

## 🎯 Advanced Features

### Deep SEO Mode
When requested, performs:
- Competitor analysis (top 5-10 articles)
- Keyword gap analysis
- Featured snippet optimization
- People Also Ask integration

### Content Brief Mode
Creates detailed planning with:
- Word count targets per section
- Must-cover subtopics
- Related content for linking
- Content depth indicators

### Persona Analysis
Develops detailed audience profiles:
```json
{
  "primaryPersona": {
    "name": "Developer Dana",
    "expertise": "intermediate",
    "goals": ["learn quickly", "implement solutions"],
    "painPoints": ["complex documentation"]
  }
}
```

## 📄 Example Outputs

### Example style.json
```json
{
  "blogTitle": "Getting Started with React Hooks",
  "slug": "getting-started-react-hooks",
  "audience": "intermediate developers",
  "tone": "conversational",
  "voice": "first-person",
  "keyKeywords": ["React Hooks", "useState", "useEffect"],
  "structure": {
    "hookType": "question",
    "voidToFill": "Confusion about when and how to use React Hooks",
    "sections": [
      {
        "heading": "What Are React Hooks?",
        "subPoints": ["Definition", "Purpose", "Benefits"]
      }
    ]
  }
}
```

### Example Blog Structure
```markdown
# Getting Started with React Hooks

Have you ever felt overwhelmed by React class components and wished for a simpler way?

[Introduction explaining the problem...]

## What Are React Hooks?

![Image: React Hooks conceptual diagram](placeholder)

[Content with examples...]

```javascript
// Code example with breakdown
const [count, setCount] = useState(0);
```

[Explanation of code...]

## Conclusion

[Call-to-action...]
```

### Sample Templates
We've added sample templates in the `templates/` directory to help you get started:
- **templates/reference.md**: A template for creating reference files used for fact-checking and research.
- **templates/example.md**: A sample blog post demonstrating recommended writing style, structure, and elements like code blocks.

## 💡 Use Cases

### 1. Technical Tutorials
- Step-by-step guides with code examples
- Breakdown complex concepts
- Include visual diagrams

### 2. Thought Leadership
- Industry insights
- Opinion pieces
- Trend analysis

### 3. Product Reviews
- Structured comparisons
- Pros and cons analysis
- User experience focus

### 4. How-To Guides
- Practical instructions
- Problem-solving approach
- Clear outcomes

### 5. SEO-Focused Content
- Keyword-optimized articles
- Featured snippet targeting
- Long-tail keyword integration

## 🤝 Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution
- Additional blog templates
- SEO optimization strategies
- Language-specific code formatting
- Industry-specific adaptations

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by modern content creation best practices
- Built for writers who want structure without rigidity
- Designed to evolve with your needs

---

**Created with ❤️ for content creators who value quality and efficiency**
