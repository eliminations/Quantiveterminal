# Vercel Deployment Instructions

To deploy this project to Vercel:

1. **Set Root Directory in Vercel Dashboard:**
   - Go to your Vercel project settings
   - Navigate to "General" → "Root Directory"
   - Set it to: `whitelabel-landing`
   - Save the changes

2. **Alternative: Deploy from whitelabel-landing directory**
   - If you prefer, you can deploy directly from the `whitelabel-landing` directory
   - The `vercel.json` in that directory is already configured

3. **Deploy:**
   - Push your code to GitHub
   - Vercel will automatically deploy
   - Or use `vercel` CLI from the root directory

The `vercel.json` at the root is configured with security headers and clean URLs. Make sure to set the Root Directory to `whitelabel-landing` in your Vercel project settings to avoid 404 errors.
