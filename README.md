# ✨ CosmicVoyage - A Futuristic Space Travel Agency ✨

## Check Live Link here  -> [Link](https://hackathonnsit.netlify.app/) ⭐

![Demo App Image 1](./public/1.png)
![Demo App Image 2](./public/2.png)
![Demo App Image 3](./public/3.png)


## Technologies Used
- **Frontend**: React.js+vite
- **Styling**: Daisy Ui, Shadcn, and custom Tailwind CSS for responsive design
- **Version Control**: Git & GitHub


## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/Neel-max-cpu/NsitHackthon.git
```


### Step 2: Navigate to the Project Directory
Change into the project directory:
```
cd frontend
```


### Step 3: Install Dependencies
Run the following command to install the necessary dependencies for the frontend and backend:
```shell
npm install
```
or 

```shell
npm i
```

### Start the app
Run the frontend 

```shell
npm run dev
```
https://verpex.com/blog/website-tips/how-to-create-shapes-with-inner-curves-using-css-mask
 make this class and put this class in a div eg.
<div className='inverted-radius h-200px w-full'></div>
.inverted-radius {
  --r: 20px; /* the radius */
  --s: 30px; /* size of inner curve */
  --x: 50px; /* horizontal offset (no percentage) */
  --y: 10px; /* vertical offset (no percentage) */
  
  --_m:/calc(2*var(--r)) calc(2*var(--r)) radial-gradient(#000 70%,#0000 72%);
  --_g:conic-gradient(at calc(100% - var(--r)) var(--r),#0000 25%,#000 0);
  --_d:(var(--s) + var(--r));
  mask:
    calc(100% - var(--_d) - var(--x)) 0 var(--_m),
    100% calc(var(--_d) + var(--y)) var(--_m),
    radial-gradient(var(--s) at 100% 0,#0000 99%,#000 calc(100% + 1px)) 
     calc(-1*var(--r) - var(--x)) calc(var(--r) + var(--y)),
    var(--_g) calc(-1*var(--_d) - var(--x)) 0,
    var(--_g) 0 calc(var(--_d) + var(--y));
  mask-repeat: no-repeat;
}

