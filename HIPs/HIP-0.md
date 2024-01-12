---
DIP: 0
Title: HIP Purpose and Guidelines
Status: Active
Themes: Meta
Tags: Other
Authors: bitbeckers (@bitbeckers)
Discussion: [TBD]
Created: 2024-01-12
---

## What’s a HIP?

HIP stands for Hypercert Improvement Proposal. A HIP is a proposal put forth by members of the community describing a desired new feature or process to improve hypercerts and/or it's ecosystem. A HIP should be concise and provide as much information as possible as well as a rationale for the proposal.

The HIP author is responsible for making the case for a proposed HIP, and community members will be able to comment on it. It is up to the hypercerts team to choose which proposals are considered, reviewed, and accepted.

These are our first steps into community, governance and decentralization. We are excited to see all of your great ideas!

## Rationale

The hypercerts team intends HIPs to provide a mechanism for collecting collaborative community input on what should be worked on for hypercerts and the interconnected impact funding network we're building. While we are excited to have a more formal process to hear ideas from the community (roughly inspired by the more decentralized PEP, BIP and EIP processes - and in the case of HIPS mostly [DIPS](https://github.com/efdevcon/DIPs/)), this is an experiment, and it should be understood that approval of proposals ultimately lies solely with the hypercerts team. HIPs focus on collaboration in the ecosystem, so please review and collaborate on other proposals rather than submitting possible duplicates.

## Themes

Here is a list of themes to inspire you:

- **Attestations** - The hypercerts protocol in and of itself are impact claim, and attestations are the way to verify them. This theme is about improving the way attestations are created, verified, and used.
- **Value flows** - Combining the hypercerts protocol with the marketplace and evaluations can unlock novel funding mechanisms or improve existing ones.
- **Collaboration** - The hypercerts protocol is a collaborative effort, and we want to encourage collaboration across teams and projects.
- **Infrastructure** - The hypercerts protocol is a public good, and we want to make sure it is accessible to everyone. This theme is about improving the infrastructure that supports the hypercerts protocol.
- **Meta** - Any improvement to the HIP process itself. This process is new, and it could benefit from anything that you’ve got in mind. We’d love to hear your thoughts.

## Tags

Hypercerts has several aspects to its ecosystem. To help us better guide you, select the area of focus that concern your HIP:

- **Tech** - The hypercerts protocol, marketplace, SDKs, the chains we support, etc.
- **Operations** - The hypercerts team, the community, the governance, etc.
- **Collaboration** - Connecting with other projects, teams, and communities.
- **Other** - Anything else

## Resources

Your HIP may require resources from the Devcon(nect) team, so make sure to add them to your draft. This will save us both precious time when evaluating the feasibility of a HIP.

- Tech support
- Operational support
- Communication support
- Other: please specify

## Criteria for a Successful HIP

- Aligned with hypercert strategy and vision.
- Integration is driven and owned by the stakeholder/project/community
- Willing to collaborate with other projects and people
- FOSS mentality

## Team

The hypercerts team is the final decision maker on the status of a HIP (Accepted - Postponed - Not Implemented). Our team will work together to provide a technical and operational review of all HIP drafts submitted. They are responsible for communicating with the HIP authors and relaying information between teams, and accompany projects through their production-implementation phase to ensure Accepted HIPs are realised.

## Workflow (From Idea to Implementation)

#### 1. Eureka!

You, the HIP author, just came up with a great idea💡 for hypercerts.

#### 2. Community Feedback

Before writing a formal HIP Draft in Github, take the time to vet your idea. Open a discussion thread in the [Discord forum] ( LINK TO FORUM ) and make sure to clearly state your idea to allow the community to provide feedback. Share your idea with the community to gather more feedback. This is done to ensure you don't waste your time writing a HIP that either won't get enough traction, is not feasible, or is a duplicate.

#### 3. Process

1.  **Draft HIP** - Choose your prettiest digital pen and write your HIP! Follow the yellow brick road: [HIP format](https://github.com/hypercerts-org/HIPs/blob/master/HIPs/HIP-0.md#hip-format)
2.  **Submit HIP** - Click on the scary button and submit your HIP. Ensure you include all information required in the template under HIP Format below.
3.  **Editor Review** - Your HIP is now in the hands of the HIP editors team for review.
    Editors might request more information and ask to resubmit the HIP.
4.  **Hypercerts team Review**
    - **Draft** - Your HIP that is undergoing rapid iteration and changes
    - **Accepted** - Your HIP idea is approved! Now it's time to work on the implementation!
    - **Not Implemented** - Oh no, the mean hypercerts team, reach out to them and ask for more context to understand their reasoning if no feedback was provided.
    - **Changes Requested** - The HIP needs modifications conditional to its validation.

#### 4. Implementation

- Definition of project timeline
- Monthly sync with HIP editors & other HIP-authors; or as needed.
- Collaboration with other HIP projects
- Testing

#### 5. Production

- Ready for take-off!

## HIP Format

Your first PR should be a first draft of the final HIP. It must meet the formatting criteria (largely, correct metadata in the header). An editor will manually assign it a number before merging it. Make sure you include a discussions-to header with the URL to the [ Discord forum ]( LINK TO DISCORD FORUM )

If your HIP requires images, the image files should be included in a subdirectory of the assets folder for that HIP as follows: assets/hip-N (where N is to be replaced with the HIP number). When linking to an image in the HIP, use relative links such as ../assets/hip-1/image.png.

After submitting editors will go through [this checklist](../checklist.md) - it is encouraged that you already went trough these points yourself.

All HIP should be written in markdown format. Please use the template below:

```
---
HIP: (Number of HIP)
Title: (Think of a catchy, descriptive, short title)
Status: Draft
Themes: (See themes above)
Tags: (Please select all that apply: Programming, ...)
Instances: (See instances above)
Authors: (Emails of primary contacts)
Resources Required: (dev cycles, content contribution, etc.)
Discussion: (URL of where HIP gets discussed, preferably on Discord forum)
---

-----Summary of Proposal-----
__Simple Summary__
__50 word summary__

-----Abstract-----
__200 word description of the proposal.__

-----Motivation & Rationale-----
__Below are some useful prompts__
- How would this support the hypercert ecosystem?
- How would the support connecting impact funding flows?

-----Implementation-----
__Below are some useful prompts__
- Has any part of this proposal been implemented at protocols or communities? If so, please describe how it went.
- What are the technical requirements for this proposal to be implemented?
- Can you provide visuals of what the outcome of this proposal would look like?

-----Operational Requirements & Ownership-----
__Please answer questions below:__
1. What actions are required to implement the proposal for hypercerts?
2. Who will be responsible for the proposal to be implemented effectively? (i.e. working on Day 0)
3. What other projects could this proposal be integrated with? (Bonus points for collaboration across teams :))

-----Links & Additional Information-----
__Any additional information__
```
