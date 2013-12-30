Secure Software Requirements
============================

## Confidentiality ##
 * Other than password fields, are there any other fields which should be
 masked?
 * Passwords are stored using the one-way SHA512 hashing algorithm, with salt
 and streching to 15 rounds. If other standards are required, please list them.
 * Transport layer security (TLS) is recommended for protecting transaction
 information and for PCI compliance. Specify any specific exceptions.

## Integrity ##
## Availability ##
 * Demo, staging, test server IP restrictions
 * Uptime SLA

## Authentication ##
 * Extended Validation SSL certificate
 * Integration with existing user database
   * Roles within existing users
 * Password policy
   * Should passwords be masked on the login screen?
   * What is to be [considered](http://lifehacker.com/5937303/your-clever-password-tricks-arent-protecting-you-from-todays-hackers) to be a "good enough" & "[best](http://howsecureismypassword.net/)" password?
     * Should new passwords be tested server-side?
     * Should existing passwords be tested server-side?
     * Should new passwords be tested client-side?

## Authorization ##
## Auditing ##
  * Tracking of changes (like prices)

## Session management ##
  * Automated logout
  * Concurrent session restrictions

## Errors and exceptions management ##
## Configuration parameters management ##
## Sequencing and timing ##
## Archiving ##
## International ##
  * Section 508

## Deployment environment ##
  * Code review
  * Role separation

## Procurement ##
## Antipiracy ##
