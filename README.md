owen = {
   "name": "Owen Singh",
   "roles": ["Data Analyst", "Self-taught Software Developer"],
   "education": "Master's in Computer Science",
   "location": "Cardiff, United Kingdom",
   "interests": ["Python", "Data Analysis", "Artificial Intelligence", "Machine Learning"],
   "technologies": {
       "programming_languages": ["Python", "JavaScript", "SQL"],
       "data_analysis": ["Pandas", "NumPy", "Scikit-learn", "Matplotlib"],
       "deep_learning": ["TensorFlow", "Keras", "OpenCV"],
       "web_development": ["React", "Next.js", "Node.js", "Express.js", "MongoDB", "MySQL", "Redis", "PHP", "WordPress"],
       "cloud": ["AWS"],
       "containers": ["Docker", "Kubernetes"],
       "tools": ["Git", "GitHub"]
   },
   "currently_working_on": ["BetterNet", "GeneticsGPT", "Dogefiles.io"],
   "other_projects": ["girlfriend-morning-gn-text", "discord-blogger-integration", "discord-wordpress-integration"],
   "open_source_contributions": ["Mecanik/cloudflare-image-resizing"],
   "hobbies": ["Gaming", "Programming", "Learning about AI/ML"],
   "contact": "You can reach me on Twitter @owensingh or LinkedIn /in/owensingh/",
   "fun_fact": "I'm a self-taught programmer with a passion for data analysis and artificial intelligence!"
}

print(f"Hello, I'm {owen['name']}!")
print(f"I'm a {', '.join(owen['roles'])} with a {owen['education']} from {owen['location']}.")
print(f"I'm interested in {', '.join(owen['interests'])} and work with technologies like:")

for tech_category, techs in owen["technologies"].items():
   print(f"- {tech_category.replace('_', ' ').title()}: {', '.join(techs)}")

print(f"\nCurrently, I'm working on projects like {', '.join(owen['currently_working_on'])}.")
print(f"Some of my other projects include {', '.join(owen['other_projects'])}, and I've contributed to {', '.join(owen['open_source_contributions'])}.")

print(f"\nIn my free time, I enjoy {', '.join(owen['hobbies'])}.")
print(owen["contact"])
print(owen["fun_fact"])