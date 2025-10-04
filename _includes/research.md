<h2 id="research">💡 Research Interests</h2>

<div class="research">
  <ol class="research-list">
    {% for item in site.data.research.main %}
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