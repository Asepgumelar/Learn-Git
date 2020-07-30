# Learn-Git

-Git Flow

      <clone>
      git clone -b develop <link here> <local folder name>

      <create branch>
      git checkout -b <new branch name>
      start working….
      …
      …
      …
      after work is done push using :
      git add .
      git commit -m “<commit message>”
      do Pull Request
      git push origin <branch name>
      (do this daily)

      after pull request is approved and merged do pull
      git checkout develop
      git pull origin develop
      start again from create branch
      if not don’t switch branch yet

      staging -> hasil merge dari develop
      master -> hasil merge dari staging


      chmod +x gradlew
      ./gradlew assembleBeta
