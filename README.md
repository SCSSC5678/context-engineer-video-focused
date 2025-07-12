# Context Engineer - Video Focused

A context engineering framework specifically adapted for video RAG (Retrieval-Augmented Generation) projects. This repository builds upon the original context-engineering-intro framework and extends it with video-specific capabilities.

## 🎯 Project Focus

This framework is designed to help AI coding assistants (like Claude/Cline) build robust video RAG systems by providing:

- **Video Processing Context**: Specialized PRPs for video ingestion, processing, and analysis
- **RAG Implementation Patterns**: Proven patterns for retrieval-augmented generation with video content
- **Multi-modal Integration**: Context for handling video, audio, and text data together
- **Performance Optimization**: Video-specific performance considerations and best practices

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Git
- Access to video processing libraries (will be defined in project PRPs)

### Installation
```bash
git clone https://github.com/SCSSC5678/context-engineer-video-focused.git
cd context-engineer-video-focused
pip install -r requirements.txt
```

## 📁 Project Structure

```
context-engineer-video-focused/
├── .claude/                    # Claude/Cline configuration
│   ├── commands/              # Enhanced PRP commands
│   └── settings.local.json    # Local settings
├── PRPs/                      # Project Requirement Prompts
│   ├── templates/             # PRP templates
│   └── knowledge_base/        # Failure patterns & success metrics
├── examples/                  # Example implementations
├── Enhanced Directory/        # Setup scripts
├── INITIAL.md                # Project feature definition
├── CLAUDE.md                 # Claude-specific instructions
└── context_engineering_utils.py  # Utility functions
```

## 🎬 Video RAG Workflow

### 1. Video Ingestion
- Video file processing and segmentation
- Audio extraction and transcription
- Frame extraction and analysis
- Metadata extraction

### 2. Content Processing
- Multi-modal embedding generation
- Temporal alignment of video/audio/text
- Semantic chunking strategies
- Index creation and optimization

### 3. RAG Implementation
- Query processing and routing
- Multi-modal retrieval strategies
- Context assembly and ranking
- Response generation with video references

### 4. Performance Optimization
- Caching strategies for video content
- Efficient storage and retrieval
- Real-time processing considerations
- Scalability patterns

## 🛠 Development Workflow

### Using PRPs (Project Requirement Prompts)

1. **Define Feature**: Create or update `INITIAL.md` with your video RAG feature
2. **Generate PRP**: Use `.claude/commands/generate-prp.md` to create comprehensive requirements
3. **Validate**: Use `.claude/commands/validate-prp.md` to check completeness
4. **Execute**: Use `.claude/commands/execute-prp.md` to implement
5. **Analyze**: Use `.claude/commands/analyze-prp-results.md` to review results

### Git Workflow

```bash
# Create feature branch
git checkout -b feature/video-ingestion

# Make changes and commit
git add .
git commit -m "Add video ingestion pipeline"

# Push and create PR
git push origin feature/video-ingestion
```

### Branch Strategy
- `main`: Stable, production-ready code
- `feature/*`: New features and enhancements
- `bugfix/*`: Bug fixes
- `experiment/*`: Experimental features

## 📚 Key Components

### Enhanced Research Process
The framework includes enhanced research capabilities specifically for video RAG:

- **Multi-layered Research**: Concepts → Implementation → Edge Cases → Community Insights
- **Tech Stack Awareness**: Automatic detection of project dependencies
- **Sequential Thinking**: Complex problem breakdown using `sequentialthinking` MCP tool
- **Quality Sources**: Integration with Perplexity and Context7 MCP for documentation

### Video-Specific Considerations
- **Format Support**: MP4, AVI, MOV, WebM, etc.
- **Processing Libraries**: FFmpeg, OpenCV, MoviePy integration patterns
- **ML Models**: Video understanding models (CLIP, VideoBERT, etc.)
- **Storage**: Efficient video storage and retrieval strategies
- **Streaming**: Real-time video processing considerations

## 🔧 Configuration

### Claude/Cline Settings
The `.claude/settings.local.json` file contains permissions for:
- File operations (read, write, search)
- Command execution (Python, testing, linting)
- Web fetching for documentation

### MCP Integration
This project leverages several MCP (Model Context Protocol) servers:
- **Sequential Thinking**: For complex problem solving
- **Perplexity**: For research and documentation
- **Context7**: For library documentation
- **GitHub**: For repository operations

## 📖 Documentation

- `IMPLEMENTATION_GUIDE.MD`: Detailed implementation guidance
- `CLAUDE.md`: Claude-specific instructions and context
- `PRPs/templates/`: PRP templates for different feature types
- `PRPs/knowledge_base/`: Failure patterns and success metrics

## 🎯 Video RAG Use Cases

### Content Creation
- Video summarization and highlights
- Automatic chapter generation
- Content recommendations
- Multi-language subtitle generation

### Education
- Lecture content search and retrieval
- Interactive video learning
- Knowledge extraction from educational videos
- Personalized learning paths

### Entertainment
- Movie/TV show content analysis
- Scene search and retrieval
- Character recognition and tracking
- Mood-based content recommendations

### Business
- Meeting recording analysis
- Training video search
- Product demo organization
- Customer support video libraries

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Update documentation
6. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Original context-engineering-intro framework by [coleam00](https://github.com/coleam00)
- Claude/Cline development team
- MCP (Model Context Protocol) contributors

## 🔮 Roadmap

### Phase 1: Foundation
- [ ] Video ingestion pipeline
- [ ] Basic transcription capabilities
- [ ] Simple RAG implementation

### Phase 2: Enhancement
- [ ] Multi-modal embeddings
- [ ] Advanced retrieval strategies
- [ ] Performance optimization

### Phase 3: Advanced Features
- [ ] Real-time processing
- [ ] Advanced video understanding
- [ ] Custom model integration

---

**Ready to build amazing video RAG applications!** 🎬✨
