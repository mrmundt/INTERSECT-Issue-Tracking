---
title: "Labelling Issues"
teaching: 5
---

::::::::::::::::::::::::::::::::::::::: objectives

- "Learn how to use labels for GitHub issues."

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- "How do you make and assign labels to issues?"

::::::::::::::::::::::::::::::::::::::::::::::::::

## GitHub Labels

Each new GitHub repository comes with a set of default labels that can be
assigned to issues, pull requests, or discussions.

From [GitHub's official documentation](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels#about-default-labels):

| Label | Description |
| ----- | ----------- |
| `bug`   | Indicates an unexpected problem or unintended behavior |
| `documentation` | Indicates a need for improvements or additions to documentation |
| `duplicate` | Indicates similar issues, pull requests, or discussions |
| `enhancement` | Indicates new feature requests |
| `good first issue` | Indicates a good issue for first-time contributors |
| `help wanted` | Indicates that a maintainer wants help on an issue or pull request |
| `invalid` | Indicates that an issue, pull request, or discussion is no longer relevant |
| `question` | Indicates that an issue, pull request, or discussion needs more information |
| `wontfix` | Indicates that work won't continue on an issue, pull request, or discussion |

These labels can be viewed from the Issues and Pull Requests pages.

![](fig/issues-labels.png){alt='The issue page with the labels option highlighted'}

![](fig/default-labels.png){alt='The default set of labels'}

As you can see, several of these are aimed towards large, open-source communities
with many collaborators. This is not always the case in Research Software
Engineering, however, so we will need to modify these.

## Modifying Labels

Labels can be added, edited, or deleted from the labels page.

![](fig/label-highlights.png){alt='Label actions highlighted'}

Each label has three attributes:

* Label name
* Description
* Color (Hex code)

![](fig/label-attributes.png){alt='Label attributes - name, description, color'}

:::::::::::::::::::::::::::::::::::::::  challenge

## Label Maker

Navigate to your practice repository's label page.
 
* Add a new label for `discussion`
* Remove the label for `good first issue`
* Modify the color on the `wontfix` label to your favorite color

::::::::::::::::::::::::::::::::::::::::::::::::::

## Using Labels

Now that the labels are created, they can be assigned to issues.

Labels can be applied from the main Issues page or within a single issue.

From the main Issues page, simply checkmark the issue, hit the "Label"
dropdown, select your preferred label(s), and click outside of the
dropdown.

![](fig/apply-labels-issue-page.png){alt='Apply Labels from the main Issues page'}

To apply within a single issue, click on the issue to open it. Then you
will see the "Labels" option on the right-hand side.

![](fig/label-option-in-issue.png){alt='Highlighted Labels option within a single issue'}

Click on "Labels". A dropdown will appear in which you can select or deselect
your preferred label(s).

![](fig/label-dropdown-in-issue.png){alt='Label dropdown within a single issue'}

:::::::::::::::::::::::::::::::::::::::  challenge

## Stick the Label

Navigate to your practice repository's issue page.
 
* Create a new issue entitled "[YOUR NAME]'s label issue"
* Add the `discussion` label

::::::::::::::::::::::::::::::::::::::::::::::::::

## Filter by Labels

Another feature of labels within GitHub is the ability to filter issues by
them. This is a powerful and useful feature for any project that uses
GitHub Issues for tracking, organizing, and prioritizing work.

To filter, navigate to the main Issues page. With no issue selected, click the
"Labels" dropdown again. You'll see that this dropdown now says "Filter by
label" rather than "Apply labels."

![](fig/filter-by-label.png){alt='Filter by label dropdown on main Issue page'}

Click on a label in the list to filter by it. GitHub will only show issues
that have that label applied.

You can select multiple labels or use the hints at the bottom of the
"Labels" dropdown to do more advanced filtering, such as exclusion.

:::::::::::::::::::::::::::::::::::::::  challenge

## Practice Filtering

Navigate to [https://github.com/spack/spack](https://github.com/spack/spack) and
find the issues page.
 
* Filter by the `architecture` label
* Filter by both the `architecture` and `architectures` labels
* (CHALLENGE) Filter by `question` but exclude `bug`

::::::::::::::::::::::::::::::::::::::::::::::::::

You now understand how to make, change, apply, and filter by labels in
GitHub Issues.

:::::::::::::::::::::::::::::::::::::::: keypoints

- "Labelling issues can help with organization and filtering."

::::::::::::::::::::::::::::::::::::::::::::::::::

