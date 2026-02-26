# Mitsubishi Electric Distributor Website

LiTong Group - Authorized distributor of Mitsubishi Electric automation products.

## Site Structure

- `/` - Homepage
- `/products/` - Product categories (PLC, Servo, Inverter, HMI)
- `/solutions/` - Industry solutions
- `/support/` - Technical support
- `/news/` - Company and industry news
- `/about/` - Company information
- `/contact/` - Contact information

## Features

- Fully responsive design
- SEO optimized
- Mobile-friendly navigation
- Fast loading performance

## Technology Stack

- HTML5
- CSS3 (Grid/Flexbox)
- JavaScript (ES6+)

## Deployment on Cloudflare Pages

### Step 1: Connect GitHub Repository

1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Go to **Workers & Pages** > **Create Application**
3. Select **Pages** > **Connect to Git**
4. Select repository: `befpail737-glitch/mitisubishi`

### Step 2: Configure Build Settings

- **Build command**: `echo "Build not required for static site"`
- **Build output directory**: `./`
- **Root directory**: (leave empty)

### Step 3: Environment Variables (Optional)

No environment variables required for this static site.

### Step 4: Deploy

1. Click **Begin Setup**
2. Click **Save and Deploy**
3. Cloudflare Pages will build and deploy your site

### Step 5: Configure Custom Domain

1. Go to **Custom Domains** in Cloudflare Pages dashboard
2. Add your domain: `mitsubishi.elec-distributor.com`
3. Follow DNS configuration instructions

### Automatic Deployments

- Every push to `main` branch will trigger automatic deployment
- Pull request previews are available
- Rollback to previous deployments is supported

## Local Development

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Open browser
http://localhost:8000
```

## Contact

- WhatsApp: +86 15013702378
- WeChat: +86 18612518271

## License

Proprietary - LiTong Group
