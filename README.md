[![Netlify Status](https://api.netlify.com/api/v1/badges/0600a486-0a69-401e-af6e-516b6275ce17/deploy-status)](https://app.netlify.com/sites/molyday/deploys)

module.exports = {
  plugins: [
    {
      resolve: `gatsby-theme-blog`,
      options: {
        /*
        - basePath defaults to `/`
        */
        basePath: `/blog`,
      },
    },
  ],
}
