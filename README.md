# RenoWise Variation Approval Page

This is a professional, responsive web page for client variation approvals.

## Features

- 🎨 Modern, professional design with animations
- 📱 Mobile-responsive layout
- 🔄 Real-time data loading from Supabase API
- ✅ Approve/Decline functionality
- 📄 PDF download integration
- 🖼️ Photo gallery support
- 🎯 Professional branding support

## Deployment to Netlify

### Option 1: Drag & Drop (Easiest)

1. Go to [netlify.com](https://netlify.com) and sign up/login
2. Drag the entire `approval-page` folder to the Netlify deploy area
3. Your site will be live instantly with a URL like `https://amazing-name-123456.netlify.app`

### Option 2: Git Integration (Recommended for updates)

1. Create a new repository on GitHub
2. Upload the `approval-page` folder contents to the repository
3. Connect the repository to Netlify
4. Auto-deploy on every update

## Configuration

Once deployed, update the following:

1. **Update Supabase function**: Change the redirect URL in `review-variation/index.ts`
2. **Update email template**: Use the new Netlify URL in approval emails
3. **Test the workflow**: Send a test variation approval

## URL Structure

The approval page expects a token parameter:
```
https://your-site.netlify.app/?token=APPROVAL_TOKEN
```

## Customization

- **Colors**: Update CSS variables in the `<style>` section
- **Logo**: The page automatically loads organization logos from the database
- **Branding**: Customize fonts, colors, and styling as needed

## Support

This page integrates with:
- Supabase Edge Functions for data loading
- PDF generation service
- Email approval system
- Photo/media display
