# How to contribute

The Project Nebula team welcomes contributions to our public repos. We want to
keep it as easy as possible to contribute changes that get things working in
your environment. Your additions could help other users with similar needs. 
Before you get started, there are a few guidelines that we need contributors to
follow.

## Examples and steps

This repo is where we keep example workflows that you can use to get started
with Nebula. You can contribute your own workflows for tools that are not
sufficiently covered in the existing example workflows. 

If you're interested in
contributing your own Nebula step image, head over to our
[nebula-steps](https://github.com/puppetlabs/nebula-steps) repo. 

To find out more about Nebula workflows and steps, see [Using
workflows](https://puppet.com/docs/nebula/beta/using-workflows.html).

## Getting Started

1. Fork this repository on GitHub. If you don't have a GitHub account, you can
   sign up for free on the [GitHub](https://github.com/join) website.
2. Create a feature branch based on `master`. For example,
```
git checkout -b new-example/master/my_contribution master
```
3. When you're done authoring and testing your workflow, push the changes to
   your fork, and open a PR to `master`.
4. Remember to follow the file content and structure guidelines listed below. 
5. Include a detailed commit message.
6. Request a review from the `nebula-community` team.

## File content and structure

### Naming conventions
The files associated with your workflow should be in a new, child directory of
`example-workflows`. Follow these naming conventions:
- Give your workflow directory a descriptive name. 
- Try to start the name with a verb.
- Separate the words with hyphens.
- Use lowercase.

For example, `provision-aws-cluster-with-terraform`

### Directory structure

Your directory should contain the your workflow file, a `metadata.json` file,
and a `README.md` file.

#### Workflow guidelines

Your workflow file should:
  - Use the same name as the parent directory.
  - Use the `.yaml` extension.
  - Contain valid YAML and follow the Nebula step conventions explained at .

For example, `provision-aws-cluster-with-terraform.yaml`

#### `metadata.json` guidelines

TBD

#### README guidelines

Your README file should guide a user through your workflow. Make sure you
include any prerequisites, such as accounts, and permissions levels. Use
the other READMEs in this repo as a guide.


