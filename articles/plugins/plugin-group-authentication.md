<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group / Display title: Authentication Group -->

## Group Description

The plugins in this group are used for standard user login to the Site or Administrator interfaces. The default is Joomla Authentication. The *Cookie* method is used in conjunction with the *Remember Me* function for Site login only. The cookie is set after first login with one of the other methods.

## Authentication - Cookie

![cookie authentication plugin](../../../en/images/plugins/plugin-authentication-group-cookie.png)

- **Cookie Lifetime** The number of days until the authentication cookie will expire. Other factors may cause it to expire before this. Longer lengths are less secure.
- **Key Length** The length of the key to use to encrypt the cookie. Longer lengths are more secure, but they will slow performance.

## Authentication - Joomla

This plugin processes the default User Authentication method in Joomla. It has no options.

## Authentication - LDAP

This plugin processes User Authentication against an LDAP server.

![ldap authentication plugin](../../../en/images/plugins/plugin-authentication-group-ldap.png)

- **Host** The host URL. For example, `openldap.mycompany.org`.
- **Port** The port number. The default is 389.
- **LDAP V3** Whether or not this host uses LDAP version 3. The default is LDAP v2.
- **Negotiate TLS** Whether or not to use TLS encryption with this host. If set to *Yes*, all traffic to and from this server must be encrypted.
- **Follow Referrals** Whether to set the LDAP_OPT_REFERRALS flag to Yes or No. For Windows 2003 hosts this must be set to No.
- **Authorization Method** *Bind Directly as User* or *Bind and Search*.
- **Base DN** The Base DN of your LDAP server.
- **Search String** A query string used to search for a given User. The `[search]` keyword is replaced by the login typed by the User. For example: `uid=[search]`. More than one Search String can be entered. Separate each by a semi-colon `;` character. This is only used when searching.
- **User's DN** The [username] keyword is dynamically replaced by the username typed by the User. An example string is: `uid=[username], dc=[my-domain], dc=[com]`. More than one string can be entered. Separate each with a semi-colon `;` character. This is only used if the Authorization Method above is set to *Bind Directly as User*.
- **Connect Username and Connect Password** These define connection parameters for the DN lookup phase. For anonymous lookup, leave both of these fields blank. For an Administrative Connection, the *Connect Username* is the username of an administrative account (for example, *Administrator*). In this case, the *Connect password* is the actual password to this administrative account.
- **Map: Full Name** The LDAP attribute that contains the User's full name.
- **Map: Email** The LDAP attribute that contains the User's email address.
- **Map: User ID** The LDAP attribute that contains the User's login ID. For Active Directory, this is `sAMAccountName`.
- **Debug** Enables debug hardcoded to level 7.
