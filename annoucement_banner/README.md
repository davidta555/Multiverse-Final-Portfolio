## Banner Integration with CDaaS

One feature I have work on at American Express is Banner Integration with CDaaS on Hydra PaaS Platform (JF 2.3 | JF 2.4 | JF 2.5 | JF 2.7).

This feature will allow Cloud Engineering teams to quickly and easily update the banner text at the top of the Hydra Console through use of the CDaaS tool. Content Delivery as a Service (CDaaS) is the Cloud Solutions content delivery network (CDN). CDaaS is built on NGINX+, providing the ability to offload static web content from a Web application. The banner will be visible from the main page of the Hydra console.

The main audience for this feature are cloud engineering teams and application teams. Cloud Engineering teams (Cloud Ops/Solutions/Product Management) can share important information with application teams with less time and effort. While application teams will benefit by receiving more accurate and up-to-date information about the Hydra platform, including platform stability, and information about new releases and capabilities.

The reasoning behind the need and creation for this feature was, originally, information regarding maintenance, outages, migration, etc. were spread through work of mouth and separate pages. So, there were gaps in information and not all teams would be informed in a timely manner. This feature helps all teams to know important information and enables them to plan more effectively.

One of the challenges I faced was because of security issues at one point I could not view the changes of CDaaS on my local enviroment and only on the production enviroment. So every change I made, I would have to temporarily deploy my code on offline hours to view my changes (JF 4.3).

## Technologies

- React
- Redux
- Golang
- Jenkins
- OpenShift

## Competencies
- JF 2.3 Can develop effective user interfaces
- JF 2.4 Can create simple software designs to effectively communicate understanding of the program
- JF 2.5 Can implement a responsive User Interface
- JF 2.7 Effectively manages state for complex User Interfaces
- JF 4.3 Is able to build, manage and deploy code into the relevant environment
