
---

# Happy Birthday web

A customizable web-based birthday card to wish your friends and family in a unique way.

Check out the previews:

- [Without Scroll Message](https://happy-birthday-card.vercel.app/)
- [With Scroll Message](https://hbd-card.netlify.app/)

If you liked it, please consider giving it a star 🤩⭐. You can also support me by sponsoring.

---

## How to Set Up

Here are the methods to set it up for yourself.

### Remote Deployment

- Vercel Deploy

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FAsimbaloch%2FBirthday_wish&env=NAME,PIC&envDescription=NAME%20-%3E%20Name%20of%20the%20Receiver%20%7C%20PIC%20-%3E%20web%20url%20of%20a%20picture%20of%20the%20receiver&envLink=https%3A%2F%2Fgithub.com%2FAsimbaloch%2FBirthday_wish%2Fblob%2Fmain%2Fdocs%2Fvariables.md&project-name=birthday-wish&repo-name=birthday-wish&demo-title=Happy%20Birthday%20Card&demo-description=This%20is%20a%20web%20based%20interactive%20birthday%20card.&demo-url=https%3A%2F%2Fhappy-birthday-card.vercel.app%2F&demo-image=https%3A%2F%2Ftelegra.ph%2Ffile%2Fac886529ccc3843552f81.png)

- Netlify Deploy

   [![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Asimbaloch/Birthday_wish)

Remote deployment will require you to specify some mandatory environmental variables:

- **NAME**: Name of the receiver.
- **PIC**: URL of the picture to be loaded in the card. If you don't have the image hosted somewhere, you may publish a [telegra.ph article](https://telegra.ph) with your image and copy the image address from there.

To know more about the environment variables, check [References](#references).

### For Local Building

1. Clone the repository:

   ```sh
   git clone https://github.com/Asimbaloch/Birthday_wish
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Add a picture of the receiver in the `./local` directory. Ensure that the image is of a 1:1 ratio, or it might get cropped and squished.

4. Create a `.env` file in the root directory and add the following lines:

   ```env
   NAME='Name of the Receiver'
   PIC='name-of-image.extension'
   ```

5. Execute the following commands in order:

   ```sh
   npm run init-index-local
   npm run build:parcel
   ```

6. Upon successful execution, your built files will be ready in the `./dist` directory. Serve this directory using `live-server` or similar tools to see your card.

For further customization, check out [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)
- [Attributions](./docs/attributions.md)

---

## Support

If you have any queries or need help with deployment, you may contact me here:

- [Email](mailto:asimseom@gmail.com) <!-- Update with your email -->

<div align="center">
Made with 💖 by Asim Khan
</div>

--- 

Feel free to make any additional modifications or let me know if you need further assistance!