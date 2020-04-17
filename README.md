# Get Contract Relationships

Insert the login data in the file `Utils/credentials.json`:

Example:
```
{
"apic_ip_address": "10.10.10.10",
"apic_port": "443",
"apic_admin_user": "admin",
"apic_admin_password": "XXXXXXX",
"inventory": "Utils/inventory.yml",
"fabric_template_path": "./templates/"
}
```

then run the script:

```
$python3 get_contract_relationship.py
```

it will create the xlsx file `Contract_Relationship.xlsx`.