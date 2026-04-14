---
title: "Thanos Tsoukleidis-Karydakis"
role: "PhD Candidate"
permalink: /team/ttsoukl/
photo: "/assets/images/team/thanos.jpg"
email: ttsoukl@cslab.ece.ntua.gr
linkedin: "https://www.linkedin.com/in/thanos-tsoukleidis-karydakis-15a07a329"
---

<style>
.profile-container {
  display: flex;
  gap: 2rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.profile-image {
  flex: 0 0 250px;
}

.profile-image img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.profile-info {
  flex: 1;
}

.profile-role {
  color: var(--link-color);
  font-size: 1.2rem;
  margin-bottom: 1rem;
}

.profile-email {
  margin: 1rem 0;
  padding: 0.5rem;
  background: var(--background-secondary);
  border-radius: 6px;
  display: inline-block;
}

.profile-links {
  margin-top: 1rem;
}

.profile-links a {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.5rem 1rem;
  background: var(--background-secondary);
  color: var(--text-color);
  text-decoration: none;
  border-radius: 6px;
  transition: all 0.2s ease;
}

.profile-links a:hover {
  background: var(--link-color);
  color: grey;
}

@media (max-width: 768px) {
  .profile-container {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
}
</style>

<div class="profile-container">
  <div class="profile-image">
    <img src="{{ page.photo | relative_url }}" alt="{{ page.title }}">
  </div>
  <div class="profile-info">
    <div class="profile-role">{{ page.role }}</div>
    <p>Works on moldability and performance modeling</p>
    <div class="profile-email">
      📧 {{ page.email }}
    </div>
    <div class="profile-links">
      {% if page.linkedin %}
        <a href="{{ page.linkedin }}" target="_blank" rel="noopener noreferrer">
          🔗 LinkedIn Profile
        </a>
      {% endif %}
    </div>
  </div>
</div>