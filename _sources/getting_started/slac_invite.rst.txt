SLAC Authentication Transition 
=====================================

As announced in October 2024, SLAC has updated how we authenticate into web
resources such as SLAC Confluence and the DESC Publication Database (PubDB). To
access these resources, DESC members now need to register a SLAC-recognized
Federated Identity, an existing SLAC AD account, or create a SLAC Guest
Account. Most DESC members do not have SLAC AD accounts.

.. warning::

   If you have a SLAC Computing (Unix or AD/Windows) account, **do not** continue
   with the SLAC invitation process. Please reach out to
   `lsst-desc-help@slac.stanford.edu <mailto:lsst-desc-help@slac.stanford.edu>`_
   for assistance setting up your access to SLAC Confluence.

.. contents:: On this page
   :local:
   :depth: 1



Where to Go for Help
--------------------

Please reach out on Slack **#desc-help** or send email to
`lsst-desc-help@slac.stanford.edu <mailto:lsst-desc-help@slac.stanford.edu>`_
if you have questions.


Handling the SLAC Invitation Email
----------------------------------------

DESC members who have not yet registered a federated identity will receive an
email with the subject: **"Collaborator Invitation to SLAC resources
(LSST-DESC)"**. The contents of that email will look like this:

.. code-block:: text

   Dear Collaborator,

   You have been invited to collaborate with SLAC. Please be sure to keep this
   message until you have completed the steps.

   Your unique Invitation ID is included below. Keep it safe. This code is
   unique to you and must be used throughout this process.

   Invitation ID: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

   Step 1: Federated Login (Recommended)
   Visit this link to log into an Identity Provider:
   https://identity.slac.stanford.edu/registry/uncrowd/invite.php?invite_id=xxxxxxxxxxxx
   Enter your Invitation ID if it is not already filled in.
   You will likely not have a SLAC/Stanford account (your Confluence/Jira
   account is not a SLAC account) so you will want to search for your
   institution where it says "Enter Identity Provider Name" near the bottom
   of the page and then select it to login.

   If you are unable to locate your home institution then you should consider
   using a SLAC Guest account by searching for SLAC Guest. A SLAC Guest account
   allows you to use any working email account along with Two Factor
   authentication to be used for accessing SLAC Confluence/Jira and other
   applications. Instructions for creating and using a SLAC Guest account are
   at https://it.slac.stanford.edu/support/KB0013037.

   If you are successful you will have seen a "Thank you" web page, continue
   to Step 2.

   Step 2: Wait for Confirmation
   Your SLAC Point of Contact will reach out to you via email to inform you
   that your access to SLAC Confluence/Jira is ready. Once you have received
   that confirmation, login to SLAC Confluence using the same federated login
   you used in Step 1: https://confluence.slac.stanford.edu/
   You're done!
   It will take at least two business days for the SLAC Confluence/Jira
   administrators to assign your access to the appropriate resources.


Step 1 — Complete the Federated Login
--------------------------------------

1. Click the link provided in the invitation email.

   .. image:: https://github.com/user-attachments/assets/466d7f2a-1bf1-471a-a00d-3a941445da39
      :width: 70%
      :alt: SLAC invitation landing page

2. Enter your Invitation ID (provided in the email) if it is not already filled
   in.

3. Click **----->>   Login to an Identity Provider   <<-----**

   .. image:: https://github.com/user-attachments/assets/06a2708a-4732-4d1b-97fa-d292fd59bc97
      :width: 70%
      :alt: Identity Provider login button

4. Use the text box at the bottom of the page where it says **Enter Identity
   Provider Name** to search for your institution or affiliation. This will
   most likely be your home institution, but it could be any institution you
   are associated with.

   .. tip::

      The drop-down menu of identity providers is tedious to navigate. Use the
      text search wherever possible.

   .. warning::

      If you cannot find an institution in the list where you have credentials,
      you will need to `create a SLAC Guest Account
      <https://github.com/LSSTDESC/slac-authentication-transition/wiki/SLAC-Guest-Accounts>`_.

5. Select your institution and log in with your institutional credentials
   (your normal institution username and password). Below is an example using
   Northeastern University:

   .. image:: https://github.com/user-attachments/assets/f8b60725-15bb-4b0f-b8fb-63d06e725941
      :width: 70%
      :alt: Example institutional login screen for Northeastern University

   .. warning::

      If your institution does not provide the required set of attributes to
      authenticate with SLAC, you will see an error message. If this happens,
      start over and `create a SLAC Guest Account
      <https://github.com/LSSTDESC/slac-authentication-transition/wiki/SLAC-Guest-Accounts>`_.

6. If your login is successful, you will be returned to the "Login to your
   Identity Provider" form and see a **"Congratulations! you have completed
   federated login and Step 1 in the email instructions!"** message. Your
   username and Invitation ID should also be populated:

   .. image:: https://github.com/user-attachments/assets/2943c0d2-b4f3-4fd0-bd7b-78ed1cfdc66b
      :width: 70%
      :alt: Congratulations confirmation screen after successful federated login

7. Click **Continue** to proceed with the rest of the SLAC registration
   process. You will see a new confirmation message:

   .. image:: https://github.com/user-attachments/assets/faf7246b-b822-4666-9c51-e6a63dab8a4c
      :width: 70%
      :alt: Post-login confirmation screen

   You will receive an email with the subject **"You have been invited to join
   the SLAC Identity Portal"** sent to the same address where you received the
   original invitation.

8. Click the link in that email.

   .. image:: https://github.com/user-attachments/assets/f583622e-0582-4f17-919c-721a6f3911a4
      :width: 40%
      :alt: SLAC Identity Portal invitation email link

9. Click **Accept**.

   .. image:: https://github.com/user-attachments/assets/abad6390-6a9e-4fcf-8613-41b569f6a6f7
      :width: 70%
      :alt: Accept button on the SLAC Identity Portal

10. Click **Review Terms and Conditions**, read them, and click **Ok**. Then
    check **I Agree** and click **Submit**.

    You will see the following confirmation screen and receive an email with
    the subject **"Initial registration completed"**:

    .. image:: https://github.com/user-attachments/assets/a8282cb6-2b25-458c-a5cf-80842ab4dc81
       :width: 70%
       :alt: Initial registration completed confirmation screen


.. note::

   Once you have created your account, it will take SLAC **up to two business
   days** to enable your access to the DESC space on SLAC Confluence. You will
   be notified by email once your Confluence access is ready.
