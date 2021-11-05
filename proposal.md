# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *PyLith*

From the documentation: "PyLith is portable, scalable software for simulation of crustal deformation across spatial scales ranging from meters to hundreds of kilometers and temporal scales ranging from milliseconds to thousands of years. Its primary applications are quasistatic and dynamic modeling of earthquake faulting."
PyLith focuses on use of point-wise functions to implement governing equations,
higher order discretizations, incompressible elasticity, and use of PETSc time-stepping algorithms. The software package also provides several 2D and 3D examples that are relevant to earthquake modeling such as slips and splay faults.

PyLith is aimed at users who identify as "scientists who prefer to use prepackaged and specialized analysis tools, and experienced computational Earth scientists." I.e. the user base of PyLith has a variety of computational skill levels/abilities with developers expected to have a baseline/minimal level of programming experience.

### Stats

| Description                                           | Your answer |
|-------------------------------------------------------|-------------|
| Repository URL                                        |[https://github.com/geodynamics/pylith](https://github.com/geodynamics/pylith) |
| Main/documentation website                            |[https://pylith.readthedocs.io/en/latest/user/index.html](https://pylith.readthedocs.io/en/latest/user/index.html)|
| Year project was started                              | 2004 |
| Number of contributors in the past year               | 6 |
| Number of contributors in the lifetime of the project | 8 |
| Number of distinct affiliations                       | 5 |
| Where do development discussions take place?          | GitHub issues; [https://community.geodynamics.org/c/pylith/29](https://community.geodynamics.org/c/pylith/29); documentation site lists a mailing-list but the link was broken...|
| Typical number of emails/comments per week?           | seems like minimal discussion on GitHub; 10-20 on the forum |
| Typical number of commits per week?                   | around 10 |
| Typical commit size                                   | $<20$ files changed, $0 \to$ few thousand insertions/deletions |
| How does the project accept contributions?            | pull requests |
| Does the project have an automated test suite?        | no? not on GitLab and don't use Actions |
| Does the project use continuous integration?          | yes; checks on commits |
| Are any legal/licensing steps required to contribute? | no |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [x] I have run the test suite
- [x] The test suite passes

### Notes/concerns/risks

In general, it seems like PyLith has a pretty small community but the main contributors are very responsive to questions on the forum. PyLith is reportedly a challenge to contribute to due to requirements/system environment requirements, and integration of multiple languages.

I would like to note that this package/library was a huge pain to install; on Mac the package didn't play well with Xcode (shocking, I know) and on Linux it installed easier but the documentation/installation instructions are horrible and generally confusing since there are about 5 different ways to install the software and dependencies. I think the project would benefit a lot from better instructional documentation. 

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
