---
title: Communities (teams)
description: Explains Roblox communities and how to collaborate with multiple creators on the same experience.
---

A Roblox **community** allows multiple creators to work on the same experience, use the same assets, share profits, and give credit to all contributors.

<Alert severity="warning">
Community ownership of experiences helps creators collaborate and operate as independent studios. Roblox cannot help arbitrate or resolve disagreements if a conflict arises within a community
</Alert>

## Create a new community

Creating a community costs 100 Robux. New communities maintain certain capabilities on the legacy [Communities](https://www.roblox.com/communities) pages, but improved workflows and options for [configuring roles/permissions](#roles-and-permissions) and [inviting members](#invite-members) are only available on the [Creator Dashboard](https://create.roblox.com/dashboard/creations).

To create a new community:

1. Navigate to the [Creator Dashboard](https://create.roblox.com/dashboard/creations) and select **Create&nbsp;Community** from the **View&nbsp;As** dropdown menu.

   <img src="../assets/creator-dashboard/Nav-User-Create-Group.png" width="280" alt="Create Group option indicated for a user's account on the Creator Dashboard." />

2. On the setup page, upload an image for the group logo and enter the group name.
3. When ready, click the **Purchase** button. Once the group is created, you'll be directed to the group profile page where you can modify the group's details, including adding up to three social links.

## Roles and permissions

Group members can be assigned one or multiple **roles** within a community, and each role has **permissions** that specify the abilities of its members.

<Alert severity="warning">
Role configuration is only accessible if you're the community owner or have permission to create, configure, and assign community roles.
</Alert>

<Alert severity="error">
Roles created using the legacy [Communities](https://www.roblox.com/communities) pages will continue to operate on the legacy system and can only be managed through the legacy workflow. If permissions were granted to a legacy role, **the member will continue to have those permissions**, so it's recommended that you revoke permissions/roles in the legacy system and then migrate members to the new system.
</Alert>

1. From the [Creator Dashboard](https://create.roblox.com/dashboard/creations), select the community from the **View&nbsp;As** dropdown menu and navigate to **Collaboration**&nbsp;&rang; **Roles**.

   <img src="../assets/creator-dashboard/Nav-Collaboration-Roles.png" width="280" alt="Roles option indicated in the Collaboration section on the Creator Dashboard." />

2. For each role, carefully confirm the permissions under the **Permissions** tab.

   <img src="../assets/creator-dashboard/Group-Roles-Permissions-Tab.png" width="780" alt="Permissions tab indicated for a group role on the Creator Dashboard." />

   <table>
   <thead>
     <tr>
       <th colspan="2">Group permissions</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>**Add or remove group members**</td>
       <td>Members with this role can [invite](#inviting-members) and [remove](#removing-members) other members.</td>
     </tr>
     <tr>
       <td>**Add or remove [role] role members**</td>
       <td>Members with this role can give or remove the role to/from other members in the community This permission is useful for roles that should have some management permissions but not at the super‑admin level.</td>
     </tr>
     <tr>
       <td>**Configure limited roles**</td>
       <td>Members with this role can configure the roles they are assigned and assign permissions to those roles that they have.</td>
     </tr>
     <tr>
       <td>**Administrate all roles**</td>
       <td>Members with this role can create, delete, and configure any role in the community This is a super‑admin permission, as it provides nearly full access.</td>
     </tr>
     <tr>
       <td>**Configure group profile**</td>
       <td>Members with this role can update the community's name, description, and other metadata. It does not include transferring ownership, which only the owner can do.</td>
     </tr>
   </tbody>
   <thead>
     <tr>
       <th colspan="2">Experience permissions</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <td>**Play all community experiences**</td>
      <td>Members with this role can play all experiences owned by the community, whether they're private or public.</td>
     </tr>
     <tr>
       <td>**Edit all group experiences**</td>
       <td>Members with this role can edit all experiences and [assets](../projects/assets/index.md) owned by the community Does not include editing an experience outside of a [collaborative](../projects/collaboration.md) session or saving a place from one experience into another experience.</td>
     </tr>
     <tr>
       <td>**Edit & publish all community experiences**</td>
       <td>Members with this role can both edit experiences, as above, and also publish experiences to Roblox.</td>
     </tr>
     <tr>
       <td>**View all analytics for community experiences**</td>
       <td>Members with this role can access the [analytics](../production/analytics/index.md) of all experiences owned by the community, even if they don't have edit access.</td>
     </tr>
   </tbody>
   <thead>
     <tr>
       <th colspan="2">Community revenue</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <td>**Configure community revenue**</td>
      <td>Members with this role can view all community revenue (as&nbsp;below), and also directly manage it. This includes setting up [recurring payouts](#recurring-payouts), as well as sending [one‑time payouts](#one-time-payouts) to collaborators.</td>
     </tr>
     <tr>
       <td>**View community revenue**</td>
       <td>Members with this role can view the community's Robux balance, any configured recurring split payouts, and (in the future) new revenue logging features.</td>
     </tr>
   </tbody>
   <thead>
     <tr>
       <th colspan="2">Avatar item permissions</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <td>**Configure classic avatar items**</td>
      <td>Members with this role can configure classic avatar items such as 2D clothing.</td>
     </tr>
     <tr>
       <td>**Create classic avatar items**</td>
       <td>Members with this role can create classic avatar items such as 2D clothing.</td>
     </tr>
   </tbody>
   <thead>
     <tr>
       <th colspan="2">Open Cloud permissions</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <td>**Manage all API keys**</td>
      <td>Members with this role can upload their own [Open Cloud API keys](../cloud/open-cloud/api-keys.md) to the group, as well as configure everyone else's.</td>
     </tr>
     <tr>
       <td>**Manage own API keys**</td>
       <td>Members with this role can configure and upload their own [Open Cloud API keys](../cloud/open-cloud/api-keys.md) to the group (but not configure everyone else's as above).</td>
     </tr>
   </tbody>
   <thead>
     <tr>
       <th colspan="2">Asset permissions</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <td>**View development items**</td>
      <td>Members with this role can view development items owned by the community, for example, **Audio**.</td>
     </tr>
     <tr>
      <td>**Create and configure development items**</td>
      <td>Members with this role can upload and configure asset development items such as **Decals**.</td>
     </tr>
     <tr>
      <td>**Manage development item permissions**</td>
      <td>Members with this role can configure permissions of development items, for example, audio sharing.</td>
     </tr>
   </tbody>
   </table>

3. <Chip label="important" size="medium" variant="outlined" color="warning" /> Click the **Save Changes** button to apply the permission settings.
4. <Chip label="optional" size="medium" variant="outlined" /> Click the **Settings** tab and choose a color for the role, then click **Save&nbsp;Changes**.

   <img src="../assets/creator-dashboard/Group-Roles-Settings-Tab.png" width="780" alt="Settings tab indicated for a group role on the Creator Dashboard." />

    <img src="../assets/creator-dashboard/Group-Roles-Role-Color.png" width="780" alt="Color options indicated for a group role on the Creator Dashboard." />

   <Alert severity="info">
   A role's **Settings** section is also where community owners and members with sufficient permissions can remove a role entirely through the **Delete&nbsp;Role** button.
   </Alert>

## Manage members

Once [roles](#roles-and-permissions) have been configured for the community, members can be invited and assigned from the **Collaboration**&nbsp;&rang; **Members** page.

<img src="../assets/creator-dashboard/Nav-Collaboration-Members.png" width="280" alt="Members option indicated in the Collaboration section on the Creator Dashboard." />

<Alert severity="warning">
Member configuration is only accessible if you're the community owner or have permission to manage other members and their roles.
</Alert>

### Invite members

You can invite new members through the **Invite** button in the upper‑right corner.

<img src="../assets/creator-dashboard/Group-Members-Invite-Button.png" width="880" alt="Invite button indicated in the group's Members section on the Creator Dashboard." />

From the popup, locate a creator by typing their username into the search field. Creators will be notified when invited to your community (a customizable setting within the creator notification system), or you can copy the **community link** and share it with invited creators through other means.

<img src="../assets/creator-dashboard/Group-Members-Invite-Popup.png" width="880" alt="Invite popup window indicated in the group's Members section on the Creator Dashboard." />

### Assign roles

To assign one or more roles to a member, hover over their name, click the **&#8942;** button, and then click the **&CirclePlus;** button for the desired role.

<img src="../assets/creator-dashboard/Group-Members-Assign-Role.png" width="880" alt="Roles management popup window showing how to assign a role to a community member on the Creator Dashboard." />

To quickly un-assign a role from the members overview, hover over it and click the **&CircleTimes;** button.

<img src="../assets/creator-dashboard/Group-Members-Un-Assign-Role.png" width="880" alt="Hover-over showing how to un-assign a role from a community member on the Creator Dashboard." />

<Alert severity="error">
Currently, roles configured through the legacy [Communties](https://www.roblox.com/groups) pages appear for each member, and new members are assigned the legacy **Member** role. If permissions were granted to a role through the legacy system, **the member will continue to have those permissions**, so it's recommended that you revoke permissions/roles in the legacy system and then migrate members to the new system.
</Alert>

### Remove members

To remove a member entirely, hover over their name and click the "trash" button. A dialog will appear for you to confirm their removal.

<img src="../assets/creator-dashboard/Group-Members-Remove-Member.png" width="880" alt="Hover-over showing how to remove a member from a community on the Creator Dashboard." />

## Manage payouts

If you're the owner of a selected community, you'll find a **Payouts** page under **Finances**. Here, you can send one‑time payouts, as well as define percentage splits with other members.

<img src="../assets/creator-dashboard/Nav-Finances-Payouts.png" width="280" alt="Payouts option indicated in the Finances section on the Creator Dashboard." />

<Alert severity="info">
Some communities may not have this page unlocked initially for various reasons, such as the community having no funds to payout.
</Alert>

<Alert severity="warning">
Community owners can't share payouts across community members for experiences that charge for [paid access in local currency](../production/monetization/paid-access-local-currency.md).
</Alert>

### One-time payouts

Community owners can make one-time payouts to members in a batch, selecting a set amount for each. Safety features include 2FA challenges, confirmation dialogues, and checks around the eligibility of members being paid.

<img src="../assets/creator-dashboard/Group-Payouts-One-Time.png" width="880" alt="One-time payout button indicated in the Payouts section on the Creator Dashboard." />

### Recurring payouts

Community owners can also define recurring payouts across the entire group **and** per‑experience, assigning a percentage payout to each member before the remainder enters the community's overall balance.

<img src="../assets/creator-dashboard/Group-Payouts-Split-Options.png" width="880" alt="Split payout buttons indicated in the Payouts section on the Creator Dashboard." />

Consider the following scenario where a community experience "Laser&nbsp;Maze" is split 40%&ndash;30%&ndash;10% among three members, with a remainder of 20%.

<br />
<Grid container spacing={2}>
	<Grid item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-A.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Assuming the experience earns 1000 Robux, the three members receive 400, 300, and 100 Robux respectively (40%&ndash;30%&ndash;10%).
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-B.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	The remaining 200 Robux &mdash; 20% of the experience split&nbsp;&mdash; passes onward to the **group split** percentages, defined at 20%&ndash;20%&ndash;10% among the same three members; they receive an additional 40, 40, and 20 Robux respectively.
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-C.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	The remaining 100 Robux &mdash; 50% of the group split&nbsp;&mdash; is placed in the group's overall balance.
	</Grid>
</Grid>

<img src="../assets/creator-dashboard/Group-Payouts-Splits-Example.png" width="840" alt="Example flowchart of how experience splits are distributed to community members first, with the remainder going factored into community splits for final distribution among the community" />

<Alert severity="warning">
Note that revenue from [private server](../production/monetization/private-servers.md) subscriptions does not change if you adjust split percentages at a later time, meaning that if a player buys a private server subscription, the split percentages at the time of purchase will apply to that particular subscription forever (until it is canceled). This policy may be changed in the future.
</Alert>

## Intellectual property protection in groups

Group members with permission to edit all group experiences can enable the [Place Copying](../production/publishing/publish-experiences-and-places.md#allow-copying) setting for a creation, potentially allowing the entire Roblox community to copy it and use assets within it. To help protect intellectual property in a group, the owner or members with sufficient permissions should:

- Confirm that each member is [assigned the appropriate role](#assign-roles).
- Check that each group role has the correct [permissions](#roles-and-permissions).
- Confirm that the [Place Copying](../production/publishing/publish-experiences-and-places.md#allow-copying) setting is disabled before private assets are added.
