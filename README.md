# gitFlowTest
Repo pour tester git flow

## Etape 1 :clone le repos https://github.com/seammour/gitFlowTest.git
## Etape 2 : init git flow
Go to Git perspective and right click on your project and click on "Init Git Flow".
## Etape 3 : Creation de la branche feature/improveReadMe
right click on project --> Git flow --> Start feature. Provide a name for the feature.
## Etape 4 : import de projet feature/improveReadMe
Go to Git perspective and right click on your project and click on "Import projects".
## Etape 5 : publish  feature 
In Git perspective, right click on project --> Git flow --> publish.
Permet de publier la branche feature sur GitHub (remote) 
## Etape 6 : To get Published feature:(if team members published our features )
Right click on project --> click on gitflow --> fetch feature.
## Etape 7 : Finish feature 
In Git perspective, right click on the project --> Git Flow --> Finish Feature. You’ll see “Feature Finish Options” dialog box.

Select option #1 (Squash - produce a single commit from the changes in this feature)

Reason to select option #1:

Once feature is completed, you don't want those feature branches as it will lead to confusion when number of feature branches increases. Once feature is completed it’s good to merge into develop and delete it, so you’ll know that feature is completed.

If you’ve not committed your feature changes, it’ll ask you to "commit, stash or discard changes by resetting the current branch". 

When you select commit, provide comment and click on commit and push to publish feature changes into remote repository. At this point,
·        Feature branch 'feature/Demo-AddingFeature' was merged into 'develop'
·        Feature branch 'feature/Demo-AddingFeature' has been locally deleted
·        You are now on branch 'develop'

Now that you merged your feature code into develop branch and deleted feature branch locally, you can now go ahead and delete feature branch from remote as you’re done with that feature implementation.

## Etape 8 : Delete feature from remote
In Git perspective, right click on project --> Remote --> Push.

Enter the destination repository location --> Click “Next.

Select the feature branch name and click on “x Add Spec”. 

##Etape 9 : Push develop to remote:

In Git perspective, right click on project --> Push branch develop.
