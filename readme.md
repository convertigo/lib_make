


# lib_Integromat

This is the Integromat (Make) Connector for Convertigo No Code forms


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [forms_Integromat](#forms_integromat)
- [Mobile Library](#mobile-library)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Integromat=https://github.com/convertigo/lib_make.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Integromat=https://github.com/convertigo/lib_make/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Integromat__ project


## Sequences

### forms_Integromat

<div>Execute an Integomat (Make) Scenario by using a custom webhook. The webhook will receive all the data from the Form submitted</div>

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>doc</td><td></td>
</tr>
<tr>
<td>forms_webhook</td><td><div>The web hook you want to trigger</div></td>
</tr>
<tr>
<td>originalDoc</td><td></td>
</tr>
</table>

## Mobile Library

Describes the mobile application global properties



