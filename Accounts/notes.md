<h1>AWS ACCOUNTS</h1>
<h2>Fundamentals</h2>
An AWS Account is a container for <b>Identities</b> (users) and <b>Resources</b>.

- Need <i>unique</i> email address and a payment method.
- Account Root User (has full control over all the AWS Account and any resources created within it & can't be restricted).
- Resources bill to the AWS Account payment method as they are consumed.
- New Identities are created without permissions.
- By <i>default</i> all access to an AWS Account & resources is denied.
> [!TIP]
> AWS can contain the impact of errors/leakage -> Create seperate accounts for seperate things/teams to gain isolation.
<h2>Multi-Factor Authentication (MFA)</h2>
Uses multiple <b>Factors</b> (pieces of evidence which prove your identity).

- Knowledge: something you know (passwords,pins...)
- Possession: something you have (device, card...)
- Inherent: something you are (fingerprint, face...)
- Location: a location physical/network
> [!NOTE]
> AWS generates a (Secret Key + Additional Information) and creates a QR code.
> 
> The MFA device scan the QR code and create a virtual "device" for each account/service.
