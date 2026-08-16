# DevOps Docker & Kubernetes Hands-On Project

A beginner-to-intermediate DevOps project demonstrating containerization with Docker and application deployment to Kubernetes using a local kind cluster.

The project focuses on practical Docker and Kubernetes concepts that are commonly used by DevOps engineers.

---

## Architecture

                    Developer
                        |
                        v
                  Source Code
                        |
                        v
                  Docker Image
                        |
                        v
                 kind Kubernetes
                        |
              +---------+---------+
              |         |         |
             Pod       Pod       Pod
              |         |         |
              +---------+---------+
                        |
                        v
                    Service
                        |
                        v
                 Flask Application