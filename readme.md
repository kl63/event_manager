# Event Manager Company: Software QA Analyst/Developer Onboarding Assignment

## Github Actions:
[![CI/CD Pipline](https://github.com/kl63/event_manager/actions/workflows/production.yml/badge.svg)](https://github.com/kl63/event_manager/actions/workflows/production.yml)


## Github Issues:
- [Issue 1: Incorrect Picture URL](https://github.com/kl63/event_manager/issues/1)
- [Issue 2: Incorrect Bio Description](https://github.com/kl63/event_manager/issues/3)
- [Issue 3: RefreshTokenRequest Missing Token](https://github.com/kl63/event_manager/issues/5)
- [Issue 4: Create User Incorrect HTTP Sucess Code](https://github.com/kl63/event_manager/issues/7)
- [Issue 5: Delete User Incorrect HTTP Sucess Code](https://github.com/kl63/event_manager/issues/9)
- [Issue 6: Increse Coverage Pytest to 90%](https://github.com/kl63/event_manager/issues/11)

## Docker Image:

![Docker Image Screenshoot](/docker_image.png)

## Reflection:

During the "Event Manager" assignment, one big challenge I faced was trying to find the mistakes in the code. It felt like looking for a needle in a haystack! But once I found one mistake, it was like a light bulb moment. Suddenly, everything else became much easier to spot. It was sort of like solving a puzzle - once you find the first piece, the rest start falling into place.In terms of collaborative processes, managing different branches and coordinating my work presented its own set of challenges. Making sure that I stayed aligned with my own progress while juggling various features required clear communication and careful organization. By actively using Git for version control and GitHub for tracking issues and reviewing code, I gained a better understanding of how these tools can help in solo projects. It was like having a virtual assistant keeping track of all my tasks and helping me stay organized. This experience taught me the importance of staying disciplined and utilizing available resources effectively, even when working alone.

Looking back on theassignment, I realize how much I've grown and how many new skills and technologies I've learned. From delving into the intricacies of REST API functionality to mastering the use of Git and GitHub for version control and collaboration, each aspect of the assignment introduced me to something new. I gained hands-on experience with tools like Docker for containerization and pytest for automated testing, expanding my technical toolkit in the process. Additionally, I honed my problem-solving skills through debugging issues and implementing solutions, gaining a deeper understanding of software development practices. Overall, this assignment was not just about completing tasks but about continuous learning and growth, and I'm proud of how far I've come.


## Key Commands:
- **Start the application with Docker Compose:**
  ```bash
  docker-compose up --build

- **Run specific tests with Pytest in Docker:**
  ```bash
  docker-compose exec fastapi pytest tests/<path to test>::<test function>

- **Run Pytest with Coverage in Docker:**
  ```bash
  docker-compose exec fastapi pytest --cov

- **Apply database migrations with Alembic:**
  ```bash
  docker-compose exec fastapi alembic upgrade head


