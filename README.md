cloudinary-scala-core-repo
==========================

Compiled sources of cloudinary_scala/cloudinary-core

In Build.scala add:

val main = play.Project(appName, appVersion, appDependencies).settings(
    resolvers += Resolver.url("Andrew Boss Custom Cloudinary Core", url("https://raw.github.com/andrewboss/cloudinary-scala-core-repo/master"))(Resolver.ivyStylePatterns)
  )
