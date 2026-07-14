# Forms

## Contact form (`/contact-us/`)

**Notice above form (required):**  
Please note we do not take bookings by email. To book a taxi, use **Book Online** or call **01827 63333**.

| Field | Type | Required |
|-------|------|----------|
| Name | text | yes |
| Email | email | yes |
| Phone | tel | no |
| Subject | text | yes |
| Message | textarea | yes |

Submit → email `acorntaxisltd@gmail.com`  
Success message: Thanks — we will get back to you as soon as we can. For bookings, please use Book Online or call us.

Labels must be visible — do not use placeholder-only fields.

## Become a Driver form (`/become-a-driver/`)

| Field | Type | Required |
|-------|------|----------|
| Full name | text | yes |
| Email | email | yes |
| Phone | tel | yes |
| Do you hold a current Tamworth taxi / private hire licence? | yes/no select | yes |
| Do you have access to a licensed taxi / private hire vehicle? | yes/no select | yes |
| Additional information | textarea | no |

Submit → `acorntaxisltd@gmail.com`  
Subject prefix: `Driver enquiry — `

## Accessibility
- Associate labels with inputs
- Error messages in text (not colour alone)
- Do not block keyboard submission
