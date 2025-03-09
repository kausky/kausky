---
# Leave the homepage title empty to use the site title
title: "Aakash Kaushik | ML Engineer & Software Engineer"
date: 2024-03-09
type: landing
summary: "ML Engineer and Software Engineer specializing in generative AI, LLMs, and distributed systems. Building scalable solutions for real-world applications."
tags:
  - Machine Learning
  - Software Engineering
  - LLMs
  - Generative AI
  - MLOps
  - Cloud Infrastructure

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 📆 Book a Meeting
        url: https://calendly.com/aakash-kaushik
    design:
      css_class: dark
      background:
        gradient_start: "#87CEEB"  # Light sky blue
        gradient_end: "#1E90FF"    # Dodger blue (slightly darker)
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🔍 My Work'
      subtitle: 'Building AI Solutions with Limitless Possibilities'
      text: |-
        I'm an ML Engineer and Software Engineer 3 at Tune AI, specializing in developing and deploying machine learning models and distributed systems for real-world applications. My work focuses on creating robust AI solutions that solve complex problems and drive business value.

        ### Key Areas of Expertise:
        - **Generative AI & LLMs**: Building high-throughput proxy servers handling over 1M requests/day for OpenAI, Anthropic, and other LLM providers
        - **Document Processing**: Developing multimodal extraction pipelines processing 100K+ documents daily with ~95% precision/recall
        - **Cloud Infrastructure**: Creating flexible, scalable infrastructure across AWS, GCP, and Azure using Kubernetes and IaC
        - **MLOps**: Implementing robust monitoring, logging, and deployment pipelines for ML systems

        The name "Kausky" comes from Aakash (meaning "sky" in Hindi) and Kaushik (surname, "kau") -> kausky. This represents my vision of building AI solutions with limitless possibilities.
        
        Feel free to reach out for collaboration opportunities! 😃
        
        <div style="text-align: right; margin-top: 1.5rem;">
          <a href="uploads/resume.pdf" class="btn btn-outline-primary btn-sm" style="text-decoration: none;">📄 Download CV</a>
        </div>
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🛠️ Technical Skills'
      subtitle: ''
      text: |-
        ### Languages
        - **Golang** (2+ years): Microservices, API gateways, high-performance systems
        - **Python** (4+ years): ML/AI development, data processing, API development
        - **Others**: C++, Bash, SQL

        ### Technologies
        - **Cloud**: GCP, AWS, Azure, Kubernetes, Docker
        - **ML/AI**: PyTorch, TensorFlow, OpenVINO, LLMs, VLMs
        - **Infrastructure**: Pulumi, Terraform, CI/CD, gRPC, REST APIs
        - **Data**: Redis, MySQL, PostgreSQL, Cloud Storage (S3, GCS, Azure Blob)
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: '📄 Papers'
      subtitle: ''
      text: |-
        - **mlpack 4: A fast, header-only C++ machine learning library**  
          Published in the Journal of Open Source Software (2023)  
          [DOI: 10.21105/joss.05026](https://doi.org/10.21105/joss.05026)
    design:
      columns: '1'
  - block: markdown
    content:
      title: '🌟 Open Source Contributions'
      subtitle: ''
      text: |-
        ### Google Summer of Code - Mlpack
        As a developer for Google Summer of Code with Mlpack, I:
        - Implemented MobileNetV1 and ResNet model builders in C++, integrating pre-trained weights to reduce training time by 40%
        - Added Mean Absolute Percentage Error (MAPE) and Softmin Activation function with backward implementation
        - Spearheaded the migration of approximately 60% of core testing suite from Boost to Catch2
        - Addressed over 100 static code analysis warnings and style issues
    design:
      columns: '1'
---
