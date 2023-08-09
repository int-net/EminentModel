# Eminent Use cases

Eminent will be a tool to measure and track the maturity of an interoperability community. This section documents the use cases the tool aims to support and the actors that will be using it.


A use case diagram can be found below

![Eminent Use case Overview](../out/UseCaseModels/EminentUsecases/Emininent%20use%20cases.png)

## Actors

Actors are the typical persona's of individuals or organizations that will be using the tool. Here we describe each persona and establish who we have in mind.

### Interoperability Community

An interoperability community is a group of organizations and individuals, typically within an industry, that cooperate to achieve interoperability in a certain domain or around a specific use case. Within the energy sector this community may be comprised of, amongst others, utilities, generators, trading firms, (equipment/software/consultancy) vendors, testing facilities, governments and members of the public.
The community may be organized in umbrella organizations, but it may also be the community that is organically forming around a grassroots effort. 

In the context of interoperability maturity, the community is the most accurate object of study as interoperability is about the capacity to integrate systems (hardware, software, processes etc) across (organizational) boundaries. 

The interoperability community is an actor in the following use cases:

- Request Maturity Assessment
<!-- - Consume Maturity Assessment Report -->
- Request Maturity Tracking 
<!-- - Consume Maturity Tracking Report -->

### Community Member

A community member is a specific organization that considers itself, or is considered by others in the community, a member of the interoperability community. These organizations can belong to any of the groups mentioned in the previous section. They can be large, multi-billion euro organizations or self employed experts/consultants. 

While interoperability communities are the primary object of study for Eminent, a community member can take the maturity assessment by itself if it wishes to develop a strategy for becoming more mature at at (participating in) interoperability itself, or wishes to become more interoperable internally (interoperability across departments/teams etc).

Community Member is an actor in the following use cases:

- Request Maturity Assessment
<!-- - Consume Maturity Assessment Report -->
- Request Maturity Tracking 
<!-- - Consume Maturity Tracking Report -->

### Interviewee

The interviewee is a subject matter expert that has been indicated by the requester of a maturity assessment to fill out the questionnaire. This person is typically an Subject Matter Expert.

The Interviewee is involved in the following use case:

- Take Questionnaire
  
### Researcher

The researcher is the person or persons gathering raw questionnaire data, assisting the interviewee's, and producing Maturity Assessment Reports and Maturity Tracking Reports.

Researchers are involved in the following Use Cases:

- Create Maturity Assessment Report
- Create Maturity Tracking Report
- Process Data
  
## Use cases

Use cases are the things, typically actions, that the Eminent tool is designed to support. This section will discuss those use cases.

### Gather data through Questionnaire

The main method to gather data for the different Maturity reports, is through the questionnaire.

#### Take Questionnaire

The tool must facilitate a interviewee to answer the questionnaire.

#### Process Results

The researcher must be able to process the questionnaire results.

### Assess Maturity

An interoperability community

#### Create Maturity Assessment Report

A researcher must be able to combine questionnaire results into a Maturity Assessment Report.

#### Consume Maturity Assessment Report

An Interoperability Community must be able to receive a report describing comparing their maturity in Interoperability to the Interoperability Maturity Model.

### Track Maturity

It is desireable to track maturity over time, to get a sense if decisions, whether technical, organizational or policy-wise has positive or negative effects on interoperability.

#### Request Maturity Tracking Report

Interoperability communities and other interested parties must be able to track the maturity of an interoperability community over time.

#### Create Maturity Tracking Report

A Researcher must be able to combine results from multiple interoperability maturity assessments for the same community and use case and combine them into a trend report.