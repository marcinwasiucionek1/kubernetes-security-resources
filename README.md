# Kubernetes security: readings and resources
Welcome to this repository, a curated collection of insightful materials on securing Kubernetes manifests and environments. These resources represent countless hours of research, reading, and hands-on experimentation, and have been carefully selected for their relevance and quality.

This repository was originally created as a supplementary resource for the Kubernetes Security presentation at Sekurak Cyberstarter 2024. Whether you are just starting with Kubernetes or are an experienced practitioner, you'll find valuable guidance here to strengthen your understanding of Kubernetes security.

## General Kubernetes security
Explore foundational and advanced resources to understand the broader security aspects of Kubernetes:
- [Book: Hacking Kubernetes](https://www.goodreads.com/book/show/58153477-hacking-kubernetes) A comprehensive guide to understanding and attacking Kubernetes environments, along with defensive strategies.
- [Documentation: Kubernetes security](https://kubernetes.io/docs/concepts/security/)
Official Kubernetes documentation on key security concepts and best practices.
- [Documentation: OWASP Kubernetes Top Ten](https://owasp.org/www-project-kubernetes-top-ten/) A focused look at the most critical security risks for Kubernetes deployments, compiled by OWASP.
- [Report: The state of Kubernetes security](https://www.redhat.com/en/engage/state-kubernetes-security-report-2024) An industry report on trends, challenges, and recommendations for securing Kubernetes environments.

## Resources requests and limits
Properly configuring resource requests and limits is essential for performance and security. The following resources provide practical insights:
- [Article: For the Love of God, Stop Using CPU Limits on Kubernetes](https://home.robusta.dev/blog/stop-using-cpu-limits) A thought-provoking analysis on why CPU limits can be counterproductive in Kubernetes
- [Documentation: GKE requests and limits](https://cloud.google.com/architecture/best-practices-for-running-cost-effective-kubernetes-applications-on-gke#set_appropriate_resource_requests_and_limits) Google's guidance on setting effective resource requests and limits.

## Handling secrets
Managing secrets securely is a critical component of Kubernetes security. Learn more with these resources:
- [Conference presentation: Your (container) secret's safe with me](https://www.youtube.com/watch?v=y5gfvEO_cjY)

> When it comes to handling secrets in Kubernetes, I strongly recommend using a vault-based solutions or other secret management tools. These solutions provide enhanced security by ensuring secrets are encrypted, access is tightly controlled, and audits are maintained, significantly reducing the risk of leaks or unauthorized access.

# Explore and contribute
Feel free to explore and use these materials to deepen your knowledge of Kubernetes security. If you have feedback or suggestions for additional resources, contributions are welcome via issues or pull requests!