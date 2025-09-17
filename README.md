<h1 align="center">🤖Instagram Content Automation</h1>

<p align="center">
Automate Instagram content creation using AI: research trending topics, generate captions, review them, and create AI-generated images.
</p>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  <pre><code>git clone https://github.com/your-username/ai-instagram-content-automation.git
cd ai-instagram-content-automation</code></pre>

  <li>Install dependencies</li>
  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Set up API keys in your environment variables (<code>.env</code>)</li>
  <pre><code>
OPENAI_API_KEY=your-openai-api-key
STABILITY_API_KEY=your-stability-api-key
  </code></pre>

  <li>Run the main script</li>
  <pre><code>python main.py</code></pre>
</ol>

<hr>

<h2>🧪 Features</h2>

<ul>
  <li>📝 Research trending topics for Instagram</li>
  <li>✍️ Generate short & long Instagram captions with hashtags and CTA</li>
  <li>🔍 Review and edit captions for grammar, clarity, and engagement</li>
  <li>🎨 Generate AI-powered images using Stability AI based on content prompts</li>
  <li>📦 Fully modular Crew AI agent system</li>
</ul>

<hr>

<h2>💡 Example Usage</h2>

<p>Set a topic and kickoff the Crew:</p>

<pre><code>
topic = "The Future of Electric Cars"
result = crew.kickoff(inputs={"topic": topic})
</code></pre>

<p>The output includes:</p>
<ul>
  <li>Short & long captions</li>
  <li>Hashtags and CTA</li>
  <li>2–3 text-to-image prompts</li>
  <li>Generated images displayed in Jupyter Notebook</li>
</ul>

<hr>

<h2>📂 File Structure</h2>

<pre>
ai-instagram-content-automation/
├── instagram_content_generation_system.ipynb
├── requirements.txt
├── README.md
└── .env  (add your API keys here)
</pre>

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehedi Hassan</strong> using <code>crewai</code>, <code>langchain_openai</code>, and <code>Stability AI</code>.  
</p>

<hr>

<p align="center">⭐ Star this repo if you find it useful for automating Instagram content creation!</p>
