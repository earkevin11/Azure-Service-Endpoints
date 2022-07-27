# Azure-Service-Endpoints

# Azure Service Endpoints - Trusted Services #237
- There are SEVERAL trusted services when it comes to firewall and network settings
- There are only certain trusted services that will be allowed to bypass firewall settings
- This means Azure Disk Encryption is a trusted service when it comes to the key vault.
- Look at the Microsoft Documentation where it will give you a list of trusted services.




# Azure Key Rotation
- If you have encryption key, it's ideal to rotate/refresh the keys often. We can automate it.
- There will be configuration for you to automate the rotation of the keys.
- Permissions must be given via Access Policies
