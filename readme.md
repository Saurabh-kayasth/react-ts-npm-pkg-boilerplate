# React TypeScript NPM Package Boilerplate

A boilerplate project for creating React TypeScript npm packages with Rollup, ESLint, and Prettier.

## Features
 - Boilerplate setup for creating React **TypeScript** npm packages
 - Bundling using **Rollup**
 - TypeScript for static typing 
 - **ESLint** with TypeScript support for code linting
 - **Prettier** for code formatting
 - **Linting and formatting automation** with GitHub Actions

## Scripts
 - `npm run build`: Build the package using Rollup.
 - `npm run lint`: Run ESLint to check the code for linting errors.
 - `npm run format`: Format the code using Prettier.
 - `npm start`: Start the development server with watch mode.
  
## Development
Step 1: Install the dependencies in root project and example project:
```
npm install
```

Step 2: Start the development server in both root and example project:
```
npm start
```

## Using `npm  link` to Test Local Package
### Step 1:
Create a symlink globally for your package:
 ```bash
npm link
```
### Step 2:
Navigate to the **example** folder and run below command
```
npm link ../
```

Any changes you make to the package will be reflected immediately in the example project without the need to rebuild or reinstall the package.

# License
This project is licensed under the MIT License.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.