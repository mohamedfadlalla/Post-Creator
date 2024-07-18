# Post Creation Project

The Post Creation Project is designed to create engaging Facebook posts from various sources such as articles, research papers, and news articles. The project includes several agents that work together in a workflow to generate posts based on specified keywords or topics, tailored to fit a brand's voice and identity.

## Agents

1. **Information Extraction Agent**
   - Extracts up-to-date information about a specific topic from the internet.
   - Searches the web for the latest content from websites and papers.

2. **Source Extraction Agent**
   - Extracts all information from a specified source.
   - Outputs the extracted information into a markdown file.

3. **Relevance Decision Agent**
   - Decides which topics are most relevant for a particular brand.
   - Considers the brand's voice and identity.

4. **Markdown to Facebook Post Agent**
   - Converts markdown-formatted articles into engaging Facebook posts.
   - Tailors posts to fit the brand’s voice.

## Workflow

1. **Input**: Provide a keyword or topic to focus on.
2. **Information Gathering**: Use the Information Extraction and Source Extraction Agents to gather and extract relevant information.
3. **Relevance Analysis**: The Relevance Decision Agent filters and prioritizes the gathered information.
4. **Content Conversion**: The Markdown to Facebook Post Agent converts the filtered information into Facebook posts.
5. **Output**: Produces a specified number of posts ready for publication.

## Usage

To start using the Post Creation Project, provide a keyword or topic, and let the agents work together to generate and schedule engaging Facebook posts. The project integrates with [Jina AI Reader](https://jina.ai/reader) for enhanced information extraction.

