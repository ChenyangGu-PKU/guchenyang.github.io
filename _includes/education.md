<h2 id="education">🎓 Education</h2>

<div class="education">
  <ol class="education-list">
    {% for item in site.data.education.main %}
    <li class="experience-item">
      <div class="experience-logo">
        <img src="{{ item.image }}" alt="{{ item.title }}" class="logo-img">
      </div>
      <div class="experience-details">
        <div class="title">{{ item.title }}</div>
        <ul>
          <li>{{ item.details }}</li>
        </ul>
      </div>
    </li>
    {% endfor %}
  </ol>
</div>