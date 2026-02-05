### TEAM Kirooo

We are building an IDE extension that accepts a single GitHub repository, a single website/blog link, or multiple research PDFs as input. The system deeply understands the provided source by analyzing code, documentation, mathematical content, and logical flow — not just summarizing, but reconstructing the actual methodology behind it.

For GitHub repositories, the AI goes further by analyzing Git history, commit messages, and pull-request discussions to build a History Layer over the code. Instead of only explaining what a block does, it tells why it exists — for example: “This workaround was added in 2023 after repeated server crashes, bypassing standard validation.” This gives developers historical context and design intent, making legacy systems far easier to understand.

From this understanding, the tool automatically generates structured documentation, visual architecture diagrams, and interactive simulations so developers can clearly see how the system or algorithm works. For research papers, it converts theory into playground-style visualizations. For repositories, it builds an architectural map enriched with historical reasoning.

The core innovation is a Method Extraction Engine. Instead of producing plain explanations, the system extracts a machine-readable methodology: inputs, assumptions, core algorithm, parameters, outputs, and failure cases. This is exported as a reusable pipeline (for example, YAML + scaffolded code), turning knowledge directly into executable structure.

When multiple sources are provided (such as a paper plus its GitHub implementation), the tool performs cross-source reasoning, automatically aligning paper sections with actual code blocks and showing how theory maps to practice.

Finally, developers can click “Apply to My Data.” They upload their own dataset or project context, and the system adapts the extracted methodology to generate a customized implementation ready for their use case. The platform also integrates with LLMs, allowing developers to use custom prompts or AI-assisted coding to refine, extend, or reimplement the methodology directly inside their workflow.

In short, the product converts static knowledge into working systems — transforming papers, blogs, and repositories into visual understanding, historical context, structured methodology, and production-ready code.
