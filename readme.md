# Angular 4

This repo is intended to contain angular 4 setups;
Hoping to learn mostly by trial and error.

## Commands:
- `ng new angular-cli-workspace-example`



## Errors encounterd
- `ng generate` and `ng serve` angular.json not found
  - `PS C:\Users\praha\Documents\Learning\Angular4\projects\1> ng generate first-app
      Local workspace file ('angular.json') could not be found.
      Error: Local workspace file ('angular.json') could not be found.
      at WorkspaceLoader._getProjectWorkspaceFilePath (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\workspace-loader.js:44:19)
      at WorkspaceLoader.loadWorkspace (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\workspace-loader.js:31:21)
      at GenerateCommand._loadWorkspace (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\schematic-command.js:292:29)
      at GenerateCommand.<anonymous> (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\schematic-command.js:57:18)
      at Generator.next (<anonymous>)
      at C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\schematic-command.js:14:71
      at new Promise (<anonymous>)
      at __awaiter (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\schematic-command.js:10:12)
      at GenerateCommand.initialize (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\cli\models\schematic-command.js:56:16)
      at GenerateCommand.<anonymous> (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular\c`
- `ng serve` needs to come from the created dir+ could not find @angular dev kit build angular
  -    `Could not find module "@angular-devkit/build-angular" from "C:\\Users\\praha\\Documents\\Learning\\Angular4\\projects\\1\\angular-cli-workspace-example".
        Error: Could not find module "@angular-devkit/build-angular" from "C:\\Users\\praha\\Documents\\Learning\\Angular4\\projects\\1\\angular-cli-workspace-example".
        at Object.resolve (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular-devkit\core\node\resolve.js:141:11)
        at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\@angular-devkit\architect\src\architect.js:132:40)
        at Observable._trySubscribe (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\Observable.js:43:25)
        at Observable.subscribe (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\Observable.js:29:22)
        at DoOperator.call (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\operators\tap.js:32:23)
        at Observable.subscribe (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\Observable.js:24:22)
        at C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\util\subscribeTo.js:22:31
        at Object.subscribeToResult (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\util\subscribeToResult.js:10:45)
        at MergeMapSubscriber._innerSub (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\operators\mergeMap.js:81:29)
        at MergeMapSubscriber._tryNext (C:\Users\praha\Documents\Learning\Angular4\projects\1\node_modules\rxjs\internal\operators\mergeMap.js:76:14)
    PS C:\Users\praha\Documents\Learning\Angular4\projects\1\angular-cli-workspace-example>`
