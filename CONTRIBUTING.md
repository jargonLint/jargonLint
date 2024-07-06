# Contribution Guide

jargonLint aims to be accessible to all developers and writers, regardless of prior experience. However, we ask that you follow this guide in your contributions. This helps us support consistency and structure within the repository.

## Simple Fixes

There can be simple typos or edits to only a few lines that you want to correct.

In this case, you can simply press the "edit" option in the upper page and GitHub should guide you through:
1. Creating a fork
2. Editing the fork
3. Opening a pull request

If the GitHub suggestions you should see on the upper area are not satisfactory, and you have limited experience, you can simply open an issue for your fix. 

## Adding New Rules

We prefer to add rules that are comprehensive and widely useful. Therefore, we usually cannot accept opinionated rules that strongly differ between projects. The goal of jargonLint, after all, is to create rules that complement other style guides.

To add a new rule, we suggest following these steps:

1. Create a folder in the sources directory that carries the name of your rule without the ".yml" extension.
2. Enter the (RuleName) folder.
3. Create a "README.md" file. 
    - This file should detail your motivation, methodology, notes, and sources. 
    - Please use the template in the sources directory to write this file.
4. Append the licenses from your sources in a file named "LICENSE.OLD"
5. If useful, add any modified text that you think can be used in the future to this directory.
6. Add your rule where the naming convention is "PascalCase.yml".
7. Create a folder named "tests" and add your test files to that directory.
    - The test file with accepted phrases should be "(RuleName).good.txt"
    - The test file with denied phrases should be "(RuleName).bad.txt"
8. If useful, create a folder named "original_files" and add relevant original files to that directory.
9. Add the rule to the vale/styles/jargonLint or vale/styles/optional directory.
    - To jargonLint, if the rule is generally applicable.
    - To optional, if the rule is reserved for specific situations.
10. Add your test files to the "tests" directory in whichever directory you selected in the earlier step.

You can separate these steps into multiple pull requests. If anything seems unclear, we suggest reviewing the current rules as examples. You can also ask reach the maintainers for any suggestions or general guidance on how to add new rules.

### Optional

You can link the test files and rules across directories in the repository with GitHub actions.
In case you are not familiar with this capability, we can fulfill this step for you.

## Code Review

We will review your contribution at our earliest convenience and would appreciate your patience.

In general, we will not edit your commits and instead only suggest edits where necessary. If you disagree with our suggestions, we are open to discussing the proposed changes.

Each approved pull request by contributors will remain open until the contributor signs off or several hours have passed. If you want to delay the merging of the pull request for whatever reason, explain the reason in the comments of the pull request.

## How to Report a Bug

If you come across a bug, we ask that you answer a few questions in the issue you open:
1. Where did you use the linter, in your system or on an external server such as GitHub actions?
2. What was the result you expected?
3. What is the output instead?
4. Have you been able to replicate the issue?

## Suggestions

Please make any suggestions in [Discussions](https://github.com/jargonLint/jargonLint/discussions). You can find discussion topics related to your suggestion and check out other topics there.

## Credit

Please feel free to add yourself to the CONTRIBUTORS.md file with your pull request. We appreciate your effort and would love to add you to our list of contributors.
