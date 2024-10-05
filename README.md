<p align="center">
<img src="static/logo.png" width="800" alt="logo" />
</p>

github link (https://github.com/cfkubo/chaos-tools)

# Chaostoolkit Cloud Foundry
> Chaostoolkit Cloud Foundry [Chaos toolkit](https://github.com/chaostoolkit-incubator/chaostoolkit-cloud-foundry).



# Chaos Monkey Spring Boot
> Chaos Monkey Spring Boot [Chaos Monkey](https://github.com/codecentric/chaos-monkey-spring-boot).

### How does it work?
> If Spring Boot Chaos Monkey is on your classpath and activated with profile name `chaos-monkey`, it will automatically hook into your application.

> Now you can activate [watchers](https://codecentric.github.io/chaos-monkey-spring-boot/latest/#watchers), which look for classes to [assault](https://codecentric.github.io/chaos-monkey-spring-boot/latest/#assaults). There are also [runtime assaults](https://codecentric.github.io/chaos-monkey-spring-boot/latest/#runtime-assaults), which attack your whole application.

<p align="center">
  <img class="imgborder s1" width="90%" src="static/sb-chaos-monkey-architecture.png">
</p>




### Chaos testing is a deliberate practice of introducing failures into a system to test its resilience.

1. Define Goals and Objectives:
> Identify critical services: Determine which services are most critical to your application's functionality.
Define failure scenarios: Identify potential failure modes that could impact your critical services.
Set success criteria: Establish metrics to measure the success of your chaos testing efforts.

2. Choose a Chaos Testing Tool:
> Evaluate tools: Consider factors like ease of use, features, and compatibility with your technology stack.
Popular choices: Tools like Chaos Mesh, Litmus Chaos, Gremlin, and CF Chaos Monkey are good starting points.

3. Design Chaos Experiments:
> Create experiments: Design experiments to simulate various failure scenarios, such as network failures, hardware failures, and application errors.
Consider severity: Start with less disruptive experiments and gradually increase the severity as you gain confidence.
Automate experiments: Use your chosen tool to automate the execution of chaos experiments.

4. Prepare Your Environment:
> Isolate testing: Ensure your chaos testing environment is isolated from production to avoid unintended consequences.
Monitor systems: Set up monitoring tools to track the behavior of your application during chaos experiments.

5. Execute Chaos Experiments:
> Run experiments: Execute your designed experiments in a controlled manner.
Observe behavior: Monitor your application's performance and identify any issues or unexpected behavior.
Gather data: Collect data on the impact of failures on your application's resilience.

6. Analyze Results:
> Review data: Analyze the data collected during the chaos experiments.
Identify weaknesses: Identify areas where your application is vulnerable to failures.
Prioritize improvements: Prioritize improvements based on the severity of identified weaknesses.

7. Implement Improvements:
> Make changes: Implement changes to address the weaknesses identified in your chaos testing.
Retest: Re-run chaos experiments to verify that the improvements have been effective.

8. Iterate and Refine:
> Continuously test: Make chaos testing a regular part of your development and testing process.
Refine experiments: Refine your chaos experiments based on the results of previous tests.
Adapt to changes: As your application evolves, update your chaos testing strategies to reflect new risks and vulnerabilities.
