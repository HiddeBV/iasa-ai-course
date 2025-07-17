# IASA AI Course Copilot Instructions

## Project Architecture
This is an **IASA (International Association of Software Architects) AI Course** structured as a progressive learning journey with 6 main sections:
- `01-foundation/` - Core AI/ML concepts and implementations (12 lessons)
- `02-conduct/` - AI governance and conduct principles (2 lessons)
- `03-construction/` - AI system construction patterns (2 lessons)
- `04-automation/` - AI automation strategies (2 lessons)
- `05-asurance/` - AI quality assurance methods (2 lessons)
- `06-acceleration/` - AI delivery acceleration (2 lessons)

## Content Structure Patterns

### Lesson Organization
Each lesson follows a consistent structure:
- `assignment.md` - Core assignment prompt (always present)
- `*-solution.md` - Solution documentation (when completed)
- `*.pptx` - Presentation deliverables
- `*.md` - Supporting analysis and documentation

### Assignment Context
**Critical Context:** All assignments are role-played from the perspective of a **Chief Architect at Tinkleman Coffee Company** (international coffee importer and franchise). Key scenarios include:
- ML for coffee bean stage classification (green, first crack, second crack)
- AI chatbots for customer ordering systems
- ROI decision trees for AI projects
- DevSecOps/MLOps infrastructure decisions
- AI security, governance, and compliance

### Solution Documentation Patterns
Solutions follow enterprise presentation format:
- **Slide-by-slide breakdown** 
- **Technical implementation details** 
- **ROI analysis and business justification**
- **Implementation timelines and next steps**

## Content Generation Guidelines

### When Creating Assignments
- Frame from Chief Architect perspective at Tinkleman Coffee
- Include specific time constraints (typically 30 minutes for presentations)
- Target specific audiences (CEO, InfoSec, Enterprise Architecture, etc.) check in the assignment what the audience is


### When Creating Solutions
- Use enterprise-grade presentation structure
- Include mermaid diagrams for technical concepts
- Provide speaker notes with "Why/How/Extra" explanations
<!-- - Include specific code examples (TensorFlow, Flask, Docker patterns) -->
- Consider both technical and business stakeholder needs

### Technical Stack Preferences
Common technologies referenced:
- **ML/AI**: TensorFlow, PyTorch, Flask APIs, Docker containers
- **Cloud**: Azure-focused (per system instructions)
- **DevOps**: GitHub Actions, Azure DevOps, Kubernetes
- **Data**: MLflow, TensorBoard, data validation pipelines

## File Naming Conventions
- Assignment files: `assignment.md`
- Solution files: `{topic}-solution.md` or `{topic}-solution-notes.md`
- Presentations: Descriptive names with dates when applicable
- Supporting docs: `{topic}-{type}.md` (e.g., `rag-historical-analysis.md`)

## Quality Standards
- **Business Context**: Always tie technical solutions to coffee business operations
- **Enterprise Focus**: Solutions should address enterprise architecture concerns
- **Presentation Ready**: Content should be immediately usable in executive presentations
- **Technical Depth**: Include practical implementation details, not just theory
- **Role Consistency**: Maintain Chief Architect perspective throughout

## GitHub Best Practices
- Follow existing file organization patterns
- Use descriptive commit messages referencing lesson numbers
- Create branches for significant solution development
- Include both technical and business documentation in solutions