# Container Action Template

To get started, click the `Use this template` button on this repository [which will create a new repository based on this template](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/).

For info on how to build your first Container action, see the [toolkit docs folder](https://github.com/actions/toolkit/blob/master/docs/container-action.md).


## Environment Variables
<table>
    <tr>
        <td>
            Variable Name
        </td>
        <td>
            Required
        </td>
        <td>
            Description
        </td>
    </tr>
    <tr>
        <td>
            SLACK_WEBHOOK
        </td>
        <td>
            Yes
        </td>
        <td>
            The Webhook URL generated by Slack to send messages too.
        </td>
    </tr>
    <tr>
        <td>
            SLACK_TITLE
        </td>
        <td>
            Yes
        </td>
        <td>
            Title of the Slack message being sent.
        </td>
    </tr>
    <tr>
        <td>
            SLACK_MESSAGE
        </td>
        <td>
            Yes
        </td>
        <td>
            The message payload to be sent to Slack
        </td>
    </tr>
    <tr>
        <td>
            SLACK_ICON
        </td>
        <td>
            No
        </td>
        <td>
            The Slack user icon to use instead of the default
        </td>
    </tr>
    <tr>
        <td>
            SLACK_CHANNEL
        </td>
        <td>
            No
        </td>
        <td>
            The Slack channel to use instead of the default
        </td>
    </tr>
    <tr>
        <td>
            SLACK_COLOR
        </td>
        <td>
            No
        </td>
        <td>
            Format color to use for the Slack message
        </td>
    </tr>
    <tr>
        <td>
            SLACK_USERNAME
        </td>
        <td>
            No
        </td>
        <td>
            The Slack username to use instead of the default
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_ACTOR
        </td>
        <td>
            No
        </td>
        <td>
            GitHub Actor variable passed from Git Actions
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_REPOSITORY
        </td>
        <td>
            No
        </td>
        <td>
            GitHub Repository variable passed from Git Actions
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_REF
        </td>
        <td>
            No
        </td>
        <td>
            GitHub reference variable passed from Git Actions
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_ACTION
        </td>
        <td>
            No
        </td>
        <td>
            GitHub Action name variable passed from Git Actions
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_EVENT_NAME
        </td>
        <td>
            No
        </td>
        <td>
            GitHub Action event name variable passed from Git Actions
        </td>
    </tr>
    <tr>
        <td>
            GITHUB_WORKFLOW
        </td>
        <td>
            No
        </td>
        <td>
            GitHub Action workflow varaible passed from Git Actions
        </td>
    </tr>
</table>