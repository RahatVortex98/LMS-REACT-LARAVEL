# LMS-REACT-LARAVEL

### Frontend Part(REACT)

- Installing Vite
```
npm create vite@latest
```
- Folder name=>frontend

- To run frontend:
```
npm run dev
```
### Packages Install:
```
npm i react-router-dom
npm install react-hook-form
npm install react-hot-toast
npm install react-icons --save
npm install jodit-react --save
npm i react-simple-star-rating
npm install -D sass-embedded
npm i @hello-pangea/dnd
npm install react-filepond filepond --save
npm install filepond-plugin-image-exif-orientation
npm install filepond-plugin-image-preview
npm install filepond-plugin-file-validate-type
npm i react-player

| Command                                                | Purpose                                                                                             |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| `npm i react-router-dom`                               | Client-side routing and navigation in React applications (multiple pages without full page reload). |
| `npm install react-hook-form`                          | Simplifies form handling, validation, and form state management.                                    |
| `npm install react-hot-toast`                          | Beautiful toast notifications (success, error, loading messages).                                   |
| `npm install react-icons --save`                       | Provides popular icon libraries such as Font Awesome, Bootstrap Icons, Heroicons, etc.              |
| `npm install jodit-react --save`                       | Rich text editor (WYSIWYG editor) for creating blogs, articles, descriptions, etc.                  |
| `npm i react-simple-star-rating`                       | Star rating component for reviews and ratings. *(Your command has a typo: `stat` → `star`)*         |
| `npm install -D sass-embedded`                         | Adds SCSS/SASS support for advanced CSS styling. Installed as a development dependency.             |
| `npm i @hello-pangea/dnd`                              | Drag-and-drop functionality (reorder lists, Kanban boards, task management systems).                |
| `npm install react-filepond filepond --save`           | Modern file upload component with previews and file management.                                     |
| `npm install filepond-plugin-image-exif-orientation`   | Automatically fixes image orientation based on camera metadata.                                     |
| `npm install filepond-plugin-image-preview`            | Shows image previews before uploading.                                                              |
| `npm install filepond-plugin-file-validate-type` | Validates uploaded file types (e.g., only JPG, PNG, PDF).                                           |
| `npm i react-player`                                   | Embeds and plays videos/audio from YouTube, Vimeo, local files, and more.                           |

```

### Backend Part(LARAVEL)

- Installing Laravel

```
composer global remove laravel/installer
```
then,

```
composer global require laravel/installer
```
```
laravel new backend
```
- To run backend:
```
php artisan serve
```

- Migrate Database
```
php artisan migrate
```
