# AI-agents-for-biology
AI agents for biology: resources and papers

# AI Agents for Biology - Are We There Yet?

A comprehensive collection of resources, papers, and tools for AI agents in biological research and discovery.

## 📋 Table of Contents
- [Overview](#overview)
- [Key Papers](#key-papers)
- [Tools and Platforms](#tools-and-platforms)
- [Technical Resources](#technical-resources)
- [Current Challenges](#current-challenges)
- [Future Directions](#future-directions)
- [Contributing](#contributing)

## 🔬 Overview

AI agents represent autonomous systems that perceive their environment, make decisions, and take actions to achieve specific goals without constant human supervision. In biology, these agents are revolutionizing how we approach research, data analysis, and discovery.

### What Makes an AI Agent?

**Key Characteristics:**
- **Environmental Interaction**: Can perceive and interact with diverse environments (databases, lab equipment, code repositories)
- **Autonomy**: Operates independently with minimal human intervention
- **Memory**: Utilizes vector stores and RAG for contextual information storage and retrieval
- **Advanced Reasoning**: Powered by LLMs for strategic thinking and planning
- **Adaptive Decision-Making**: Combines perception, reasoning, and memory for goal-oriented decisions

## 📚 Key Papers

### Specialized Biological Agents

#### SpatialAgent
- **Paper**: [SpatialAgent: Multimodal AI Agent for Spatial Transcriptomics Analysis](https://www.biorxiv.org/content/10.1101/2025.04.03.646459v1)
- **Focus**: Spatial transcriptomics and gene panel design
- **Key Features**: Multi-modal annotation, cell-cell interaction analysis, cross-species support

#### CellAgent
- **Paper**: [CellAgent: An AI Agent for Single-Cell Analysis](https://www.biorxiv.org/content/10.1101/2024.05.13.593861v1)
- **Focus**: Single-cell RNA sequencing analysis
- **Key Features**: Automated task planning, tool retrieval, error handling with re-generation

#### PathFinder
- **Paper**: [PathFinder: Agentic Pathology Diagnosis with Vision-Language Models](https://arxiv.org/abs/2502.08916)
- **Website**: https://pathfinder-dx.github.io/
- **Focus**: Histopathology image analysis and diagnosis
- **Key Features**: Multi-agent triage system, automated diagnostic workflows

### Generalist Biomedical Agents

#### Biomni
- **Paper**: [Biomni: A Generalist Biomedical Agent](https://www.biorxiv.org/content/10.1101/2025.05.30.656746v1)
- **Platform**: https://app.biomni.stanford.edu/
- **Focus**: Unified biomedical action space covering multiple domains
- **Key Features**: 105+ software tools, 150+ biological databases, 59 specialized tools
- **Performance**: Top performer on Humanity's Last Exam (HLE) biomedical benchmark

#### Virtual Lab
- **Paper**: [AI agents for autonomous biological research](https://www.nature.com/articles/s41586-025-09442-9)
- **Focus**: Multi-agent collaboration for research workflows
- **Key Features**: Role-based agent specialization, collaborative research processes

## 🛠️ Tools and Platforms

### Model Context Protocol (MCP)
- **Purpose**: Standardized protocol for connecting AI agents to external tools and data sources
- **Developer**: Anthropic (open-source)
- **Biological Implementation**: [BioMCP](https://github.com/genomoncology/biomcp)

#### BioMCP Data Sources:
**Literature Sources:**
- PubMed
- bioRxiv/medRxiv  
- Europe PMC

**Genomics Sources:**
- TCGA/GDC
- cBioPortal
- 1000 Genomes Project

**Clinical Sources:**
- ClinicalTrials.gov
- NCI Database

### Active Platforms
- **Biomni Co-pilot**: https://app.biomni.stanford.edu/
- **FutureHouse Agents**: https://platform.futurehouse.org/

## 📖 Technical Resources

### Building Agents
- [Anthropic: Building Effective Agents](https://www.anthropic.com/engineering/building-effective-agents)
- [MCP Documentation](https://modelcontextprotocol.io/)

### Benchmarking
- **Humanity's Last Exam (HLE)**: Multi-modal academic benchmark
- **Website**: https://agi.safe.ai/
- **Paper**: https://arxiv.org/abs/2501.14249
- **Scope**: 1000+ academics from 500+ institutions across 50+ countries

## 🚧 Current Challenges

### Technical Challenges
- **Scalability**: Handling large databases and high-resolution images (whole-slide images)
- **Compute Requirements**: Resource-intensive operations for complex biological analyses
- **Infrastructure**: Managing connections to diverse biological databases and tools

### Operational Challenges  
- **Autonomy vs Control**: Balancing agent independence with necessary human oversight
- **Agent Interactions**: Managing and monitoring multi-agent collaborations
- **Reliability**: Ensuring reproducible and trustworthy results
- **Benchmarking**: Establishing standardized evaluation metrics

### Security and Privacy
- **Sensitive Data**: Handling clinical information and proprietary research data
- **Local Deployment**: Need for local MCP servers for high-risk databases
- **Access Control**: Managing permissions for different data sources and tools

## 🔮 Future Directions

### Near-term (1-2 years)
- **Enhanced MCP Integration**: More biological databases and tools joining the ecosystem
- **Improved Benchmarking**: Standardized evaluation frameworks for biological agents
- **Multi-modal Capabilities**: Better integration of text, images, and omics data
- **Domain Specialization**: More focused agents for specific biological subfields

### Medium-term (3-5 years)
- **Embodied AI**: Integration with laboratory robotics and automation
- **Real-time Adaptation**: Agents that learn and adapt from experimental outcomes
- **Cross-institutional Collaboration**: Agents working across different research organizations
- **Regulatory Integration**: Frameworks for using agents in clinical and regulated environments

### Long-term (5+ years)
- **Autonomous Discovery**: Agents capable of independent hypothesis generation and testing
- **Wet Lab Integration**: Full automation of experimental design and execution
- **Personalized Medicine**: Agents tailored for individual patient treatment planning
- **Global Research Networks**: Interconnected agent ecosystems for collaborative science

## 🤝 Contributing

We welcome contributions to expand this resource collection! Please consider:

- Adding new papers and preprints
- Updating tool listings and platforms  
- Sharing implementation experiences
- Suggesting new categories or applications
- Reporting broken links or outdated information

### How to Contribute
1. Fork this repository
2. Create a feature branch
3. Add your contributions with proper citations
4. Submit a pull request with detailed descriptions

## 📄 License

This collection is maintained under MIT License. Individual papers and tools maintain their respective licenses.

---

*Last updated: September 2025*
