# Docker

## What are Micro-Services and their benefits
- The idea consists of splitting your application into a set of smaller, inter-connected services that are:
	- Independently Deployable	
	- Highly maintainable
	- Loosely coupled

<p align=center>
	<img src=/imgs/microservices_diagram.jpg>
</p>

### Microservices vs Monolith Architectures

<p align=center>
	<img src=/imgs/monolith_diagram.jpg>
</p>

- When to use Monolith?
	- Small team. If you are a startup and your team is small, you may not need to deal with the complexity of the microservices architecture.
	- A simple application. Small applications which do not demand much business logic, superior scalability, and flexibility work better with monolithic architectures.
	- No microservices expertise. Microservices require profound expertise to work well and bring business value.
	- Quick launch. If you want to develop your application and launch it as soon as possible, a monolithic model is the best choice.

- When to use Microservices?
	- A complex and scalable application. The microservices architecture will make scaling and adding new capabilities to your application much easier.
	- Enough skills and expertise. Since a microservice project comprises multiple teams responsible for multiple services, you need to have enough resources to handle all the processes.

## What is Docker

- Docker is an open source containerization platform. It enables developers to package applications into containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels.

<p align=center>
	<img src=/imgs/docker_diagram.PNG>
</p>

## Why use docker instead of VMs

- Docker enables developers to easily pack, ship, and run any application as a lightweight, portable, self-sufficient container, which can run virtually anywhere.

<p align=center>
	<img src=/imgs/docker_vs_vm.PNG>
</p>

- Benefits of Containers:
	- Reduced IT management resources
	- Reduced size of snapshots
	- Quicker spinning up apps
	- Reduced & simplified security updates
	- Less code to transfer, migrate, upload workloads

#### Companies using Docker

- Companies that deploy Docker include: Business Insider, Spotify, Yelp, ADP, eBay, Expedia, Groupon, ING, New Relic, The New York Times, Oxford University Press, PayPal. Sage, Shopify, The Washington Post and Uber.


### Troubleshooting Docker

- Command to troubleshoot TTY error: `alias docker="winpty docker"`
