# Quick Documentation
1. Extrat the files in ~/Documents/LatexTemplate
2. Now add following alias to your bash script
    '''
    alias newDoc='mkdir Documentation 
                cd Documentation 
                cp -a ~/Documents/LatexTemplate/* . 
                cd ..'
    '''

3. Whenever you start a new project, just use newDoc
