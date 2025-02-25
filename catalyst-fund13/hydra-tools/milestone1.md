|Project ID|1300135|
|-----------|-------------|
|Link|[Open full project](https://projectcatalyst.io/funds/10/f13-cardano-open-developers/mesh-hydra-tools-for-administrating-and-interacting-with-hydra-heads)|
|Milestone|[Milestone 1](https://milestones.projectcatalyst.io/projects/1300135/milestones/1)
|Challenge|F13: Cardano Open: Developer|
|Milestone Budget|ADA 40,000 Ada|
|Delivered|February 17, 2025|


# Milestone Report
Hey there Milestone Reviewer, voters and everyone following the progress of this proposal.

We are glad to report on the successful completion of the first milestone of this proposal.

The acceptance criteria of this milestone have been stated as:

- 1) Hydra Provider Integration: Establish a connection with a Hydra node.
- 2) Base Functionality: Develop foundational functions to support Hydra processes across its key phases: Open, Commit, Close, and Fanout.
And here is the evidence of Milestone completion, including all relevant links to assess and audit our work.

1) Hydra Provider Integration: Establish a connection with a Hydra node.
- The entire Hydra package is done and is available at https://github.com/MeshJS/mesh/tree/feat-hydra-to-beta/packages/hydra . 
- When published, users can install it using `npm install @meshsdk/hydra`. https://www.npmjs.com/package/@meshsdk/hydra
- The Hydra Provider is available at https://github.com/MeshJS/mesh/blob/feat-hydra-to-beta/packages/hydra/src/hydra-provider.ts
  
2) Base Functionality: Develop foundational functions to support Hydra processes
- All types are defined in https://github.com/MeshJS/mesh/tree/feat-hydra-to-beta/packages/hydra/src/types 
- All functions "shapes" and inputs have been defined in https://github.com/MeshJS/mesh/blob/feat-hydra-to-beta/packages/hydra/src/hydra-provider.ts 
- Public links to the code on mesh github repository https://github.com/MeshJS/mesh/tree/feat-hydra-to-beta/packages/hydra 
We hope that all sources satisfy your assessment and audit requirements.

--- 

Note for Milestone reviewer rejection one previous PoA:

Rejection rationale has been:

"Please elaborate "When published, users can install it using `npm install @meshsdk/hydra`." or provide other proof for connection to Hydra node like screenshot or readme documentation, this is currently not evident from the submitted. Thank you." 

Dear milestone reviewer, we added a link to give some easy guidance on how to use `npm install @meshsdk/hydra`, anyway, this is a relatively simple task for developers and we dont understand why documentation on `npm install @meshsdk/hydra` should be seen as requirement for this milestone, the Proposal and its respective milestones are not for non-technical users but for experienced developers. Further, and since we fully agree that good documentation is a must have, you can see that a detailed documentation of everything in this proposal comes with the final Milestone which includes;

Updated meshjs docs for anyone to start and build on Hydra
Since we do documentation at the end of the project and not at the start, we hope that you won't request documentations in further milestones until we reach the final milestone and complete the documentation AFTER all development work has been done. 

For less experienced developers who just get started, feel free to use our guides, examples and doc's which you can find on our website at: https://meshjs.dev/ at "Resources", or join the Discord and directly get support from our crew on our Mesh Discord, find the link on the website 

Yours

Mesh Team :)


