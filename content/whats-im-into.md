---
title: "What I'm Into"
layout: "single"
url: "/whats-im-into/"
summary: "Books, movies, shows, podcasts, and links I'm currently enjoying"
---

<style>
.widgets-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.widget {
  background: var(--entry);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s, box-shadow 0.2s;
}

.widget:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.widget-header {
  display: flex;
  align-items: center;
  margin-bottom: 15px;
  padding-bottom: 10px;
  border-bottom: 2px solid var(--border);
}

.widget-icon {
  font-size: 24px;
  margin-right: 10px;
}

.widget-title {
  font-size: 18px;
  font-weight: bold;
  margin: 0;
  color: var(--primary);
}

.widget-content {
  line-height: 1.6;
}

.widget-item {
  margin-bottom: 15px;
  padding-bottom: 12px;
  border-bottom: 1px solid var(--border);
}

.widget-item:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

.item-title {
  font-weight: bold;
  color: var(--content);
  margin-bottom: 4px;
}

.item-subtitle {
  font-size: 14px;
  color: var(--secondary);
  font-style: italic;
}

.item-note {
  font-size: 14px;
  color: var(--content);
  margin-top: 6px;
}

.link-item {
  margin-bottom: 10px;
}

.link-item a {
  color: var(--primary);
  text-decoration: none;
  font-weight: 500;
}

.link-item a:hover {
  text-decoration: underline;
}

.link-description {
  font-size: 14px;
  color: var(--secondary);
  margin-top: 4px;
}

.update-date {
  text-align: center;
  color: var(--secondary);
  font-size: 14px;
  font-style: italic;
  margin-top: 30px;
  padding-top: 20px;
  border-top: 1px solid var(--border);
}
</style>

<div class="widgets-container">
  <!-- Books Widget -->
  <div class="widget">
    <div class="widget-header">
      <span class="widget-icon">📚</span>
      <h3 class="widget-title">Currently Reading</h3>
    </div>
    <div class="widget-content">
      <div class="widget-item">
        <div class="item-title">Book Title Here</div>
        <div class="item-subtitle">by Author Name</div>
        <div class="item-note">Your thoughts or progress notes go here...</div>
      </div>
    </div>
  </div>

  <!-- Movies Widget -->
  <div class="widget">
    <div class="widget-header">
      <span class="widget-icon">🎬</span>
      <h3 class="widget-title">Recent Movies</h3>
    </div>
    <div class="widget-content">
      <div class="widget-item">
        <div class="item-title">Movie Title 1</div>
        <div class="item-subtitle">Year • Director</div>
        <div class="item-note">Quick review or rating...</div>
      </div>
      <div class="widget-item">
        <div class="item-title">Movie Title 2</div>
        <div class="item-subtitle">Year • Director</div>
        <div class="item-note">Quick review or rating...</div>
      </div>
      <div class="widget-item">
        <div class="item-title">Movie Title 3</div>
        <div class="item-subtitle">Year • Director</div>
        <div class="item-note">Quick review or rating...</div>
      </div>
    </div>
  </div>

  <!-- TV Shows Widget -->
  <div class="widget">
    <div class="widget-header">
      <span class="widget-icon">📺</span>
      <h3 class="widget-title">Currently Watching</h3>
    </div>
    <div class="widget-content">
      <div class="widget-item">
        <div class="item-title">Show Title Here</div>
        <div class="item-subtitle">Network/Streaming Service</div>
        <div class="item-note">Season/episode or your thoughts...</div>
      </div>
    </div>
  </div>

  <!-- Podcasts & Music Widget -->
  <div class="widget">
    <div class="widget-header">
      <span class="widget-icon">🎧</span>
      <h3 class="widget-title">Listening To</h3>
    </div>
    <div class="widget-content">
      <div class="widget-item">
        <div class="item-title">Podcast Name</div>
        <div class="item-subtitle">Recent episode or general note</div>
      </div>
      <div class="widget-item">
        <div class="item-title">Music/Artist/Album</div>
        <div class="item-subtitle">Genre or description</div>
      </div>
    </div>
  </div>

  <!-- Links & Articles Widget -->
  <div class="widget">
    <div class="widget-header">
      <span class="widget-icon">🔗</span>
      <h3 class="widget-title">Worth Reading</h3>
    </div>
    <div class="widget-content">
      <div class="link-item">
        <a href="https://example.com" target="_blank" rel="noopener">Article Title Here</a>
        <div class="link-description">Brief description of what makes this interesting...</div>
      </div>
      <div class="link-item">
        <a href="https://example.com" target="_blank" rel="noopener">Another Great Article</a>
        <div class="link-description">Why you should read this...</div>
      </div>
      <div class="link-item">
        <a href="https://example.com" target="_blank" rel="noopener">Interesting Resource</a>
        <div class="link-description">What you'll find here...</div>
      </div>
    </div>
  </div>
</div>

<div class="update-date">
  Last updated: January 2026
</div>
