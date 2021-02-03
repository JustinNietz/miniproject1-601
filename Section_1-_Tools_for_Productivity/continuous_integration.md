# Continuous integration <img src="Images/CI_logo.png" alt="CI logo" width= 50 height=50>

Continuous integration, or shortened to CI, is a valuable and well-established practice in modern, high performance
software engineering organizations.

Using CI enables software development tasks to be developed independently and in parallel amongst the assigned
developers. Once one of these tasks is complete, a developer will introduce that new work to the CI system to be
integrated with the rest of the project.

## How to use

The foundational dependency of CI is a version control system (VCS). Once version control is in place, finding a version
control hosting platform is the next move. Most modern version control hosting tools have support and features built in
for CI. Some popular version control hosting platforms are Bitbucket, Github, and Gitlab.

After version control has been established on the project, integration approval steps should be added.

Once you have a version control system setup with some merge approval steps in place, you’ve established continuous
integration!

## How CI improves productivity

Continuous integration benefits are not limited to the engineering team but greatly benefit the overall organization. CI
enables better transparency and insight into the process of software development and delivery.

The following are some overall organizational benefits of CI.

### Enable scaling

CI enables organizations to scale in engineering team size, codebase size, and infrastructure. By minimizing code
integration bureaucracy and communication overhead, CI helps build DevOps and agile workflows. It allows each team
member to own a new code change through to release.

### Improve the feedback loop

Faster feedback on business decisions is another powerful side effect of CI. Product teams can test ideas and iterate
product designs faster with an optimized CI platform. Changes can be rapidly pushed and measured for success. Bugs or
other issues can be quickly addressed and repaired.

### Enhance communication

CI improves overall engineering communication and accountability, which enables greater collaboration between
development and operations in a DevOps team. By introducing pull request workflows tied to CI, developers gain passive
knowledge share. Pull requests allow developers to observe and comment on code from other team members. Developers can
now view and collaborate on feature branches with other developers as the features progress through the CI Pipeline.

### Adoption and installation

The challenges of continuous integration are primarily around team adoption and initial technical installation. If a
team doesn't currently have a CI solution in place, it can require some effort to pick one and get started. Thus,
considerations need to be made around the existing engineering infrastructure when installing a CI pipeline.

## CI/CD

Continuous delivery, or CD for short, is a strategy in which the development teams ensure the software is reliable to
release at any time. CI/CD come together in a pipeline.

![Git sections](Images\continuous-integration-and-continuous-delivery-pipeline.png)

There are fives stages in the CI/CD Pipeline:

**1. Version Control Phase**

In this phase of the CI/CD pipeline, the developers’ code is committed through version control software or systems such
as git, apache subversion, and more. It controls the commit history of the software code so that it can be changed if
needed.

**2. Build Phase**

This phase is the first phase of this pipeline system. Developers build their code, and then they pass their code
through the version control system or software. After this, the code returns to the build phase and gets compiled.

**3. Unit Testing and Staging**

When software reaches this stage, various tests are conducted on the software. One of the main tests is the Unit test,
in which the units of software are tested. After successful testing, the staging phase begins. As the software has
passed the tests to reach here, it is ready to be deployed into the staging process. Here, the software code is deployed
to the staging environment/server. The code can be viewed and finalized here before the final tests can be conducted on
the software.

**4. Auto Testing Phase**

After passing to the staging environment, another set of automated tests are prepared for the software. If the software
completes these tests and is proven to be deployable, it is sent to the next phase/stage, the deployment phase.

**5. Deployment Phase**

As the auto testing procedure is completed, then it is deployed to production. However, if any error occurs during the
testing phase or the deployment phase, the software is sent to the development team’s version control procedure and
checked for errors. If errors are found, then they need to be fixed. Other stages may be repeated if required.
