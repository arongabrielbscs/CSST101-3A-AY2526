---
layout: default
---

# Information

<div style="display: flex; align-items: center; gap: 20px;">
  <img src="{{'/assets/images/pfp.jpg?v=' | append: site.github.build_revision | relative_url }}" alt="Alt text" width="100" height="100">
  <div>
    <strong>Aron Gabriel L. Ogayon</strong><br>
    <em>BSCS-3A</em>
  </div>
</div>

# CSST101 - Advanced Presentation and Reasoning
In the real world, a computer scientist's job isn't just about writing code. It's about collaborating with others, explaining your work, and defending your design decisions. APR equips students with the soft skills and analytical prowess needed to excel in these areas, preparing them for roles in research, software architecture, and management where communication and reasoning are just as critical as coding proficiency. I expect that this Subject can teach me this very well.

# Projects, Assignments, and Exercises that we made.

<style>
.projects-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.project-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none;
  color: inherit;
  display: block;
  cursor: pointer;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.project-title {
  font-size: 1.2em;
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

.project-description {
  color: #666;
  line-height: 1.5;
}
</style>

<div class="projects-container">
  <a href="{{ '/propositional_logic' | relative_url }}" target="_blank" class="project-card">
    <div class="project-title">Applying Propositional Logic in Real-World Scenarios through a Mini Expert System</div>
    <div class="project-description">
      A Basic Use case of propositional logic
    </div>
  </a>
</div>

<div class="projects-container">
  <a href="{{ '/predicate_logic' | relative_url }}" target="_blank" class="project-card">
    <div class="project-title">Predicate Logic</div>
    <div class="project-description">
      A Basic Use case of predicate logic
    </div>
  </a>
</div>