# Challenges

To achieve industrial level quality of service, we need to increase
our dataset by several orders of magnitude.  Also, existing NN
architectures do not provide enough accuracy, so we have to launch a
wide exploration of a space of potential architectures.

This would require amount of GPU/TPU power that's far beyound the reach
of our small research team.

Also we acknowledge our limited knowledge and don't expect to provide
the best and the only AI for developer's tasks.  Instead we strive to
onboard best teams to provide the best solutions possible.

# Roadmap

To solve these challenges, we are planning to do an early launch of an
ecosystem, where we can bring together:

- software developers, wanting to try a new tool in their toolkit,
- owners of GPU who want to help research, and
- deep learning practitioners

We need software developers using AI to provide a steady stream of
tasks and correct solutions to them.

We need GPU operators to have vector processing power to run neural
networks on.

We need deep learning practitioners to add new promising NN
architectures to the search space.

To incentivise each party we're launching an ERC20 token on the Ethereum
network.

We will start by deploying a federated distributed deep learning system,
where GPU providers would be required to post a collateral and earn rewards
for performing deep learning tasks.

Later, we plan to focus on developing and deploying a homomorphic encryption
module for deep learning, so both AI and data providers can keep their parts
private (encrypted).

Since this is mostly R&D, we can't provide any expected launch dates.  We would
deploy updates as soon as they will be available in a quality shape.

# Integrations

Our goal is to make DevNullAI useful in a real life.

Internally we envison a simple and generic framework for managing a work
breakdown structure
([WBS](https://en.wikipedia.org/wiki/Work_breakdown_structure)).

> WBS is a hierarchical and incremental decomposition of the project
> into phases, deliverables and work packages. It is a tree structure,
> which shows a subdivision of effort required to achieve an objective

Within this there would be a project, attached to a git repository and
a list of tasks to be completed within the project.  AI would be
called out to perform a task and it will either provide human
developer a pull request with the suggested changes, or say that it
doesn't know yet how to perform this task and ask for a breakdown into
a smaller pieces.

After implementation, this framework will have open API allowing to be
integrated into widely used project management system, like Trello,
Asana, Jira, or private ones, like KavaHQ in 42 Coffee Cups.
