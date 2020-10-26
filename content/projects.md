---
# title: "Projects"
slug: "projects"
---

## Open Source Projects

{{% project
  title="lambda-edge-azure-auth"
  img="images/lambda-edge.png"
  alt="lambda-edge"
  link="https://github.com/nickshine/lambda-edge-azure-auth" %}}

A [Lambda@Edge] function that enables [Microsoft Azure AD][azure] authentication for apps using
Amazon [CloudFront].

[azure]:https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-protocols-oauth-code
[cloudfront]:https://aws.amazon.com/cloudfront/
[lambda@edge]:https://aws.amazon.com/lambda/edge/

{{% /project %}}

{{% project
  title="terraform-aws-lambda-edge-azure-auth"
  img="images/terraform.png"
  alt="terraform registry module"
  link="https://github.com/nickshine/terraform-aws-lambda-edge-azure-auth" %}}

A [Terraform Registry module][tf-registry] for [lambda-edge-azure-auth].

[lambda-edge-azure-auth]:https://github.com/nickshine/lambda-edge-azure-auth
[lambda@edge]:https://aws.amazon.com/lambda/edge/
[tf-registry]:https://registry.terraform.io/modules/nickshine/lambda-edge-azure-auth/aws/latest

{{% /project %}}

{{% project
  title="reveal.js-docker"
  img="images/reveal-docker.png"
  alt="reveal.js docker"
  link="https://github.com/nickshine/reveal.js-docker" %}}

Maintained docker images for [reveal.js] - the open source HTML presentation framework.

[reveal.js]:https://revealjs.com/

{{% /project %}}

{{% project
  title="dot"
  img="images/dot-graphviz.png"
  alt="graphviz dot"
  link="https://github.com/nickshine/dot" %}}

A Docker image for the [Graphviz] DOT CLI. Useful with `terraform graph`.

[graphviz]:https://graphviz.org/

{{% /project %}}

{{% project
  title="glt"
  img="images/glt.png"
  alt="glt"
  link="https://github.com/nickshine/glt" %}}

A command-line interface written in Node.js for GitLab tasks.

>**Note:** Deprecated. Most of this functionality has been implemented in recent versions of GitLab.

{{% /project %}}

{{% project
  title="kubernetes-pi"
  img="images/k8s-pi.jpg"
  alt="kubernetes-pi"
  link="https://github.com/nickshine/kubernetes-pi" %}}

A step-by-step build of a Kubernetes cluster from scratch with some Raspberry Pis. Used for
presentations on container orchestration.

{{% /project %}}

## Recent Contributions

{{% project
  title="semantic-release"
  img="images/semantic-release.png"
  alt="semantic-releasee"
  link="https://github.com/semantic-release/semantic-release" %}}

[Fixed a bug related to Go projects][semantic-release-nick] for [semantic-release] - a popular
automated version management and package publishing tool.

[semantic-release]:https://semantic-release.gitbook.io/semantic-release/
[semantic-release-nick]:https://github.com/semantic-release/semantic-release/commits?author=nickshine

{{% /project %}}

{{% project
  title="go-aws-news"
  img="images/go-aws-news.jpg"
  alt="go-aws-news"
  link="https://github.com/circa10a/go-aws-news" %}}

Contributed the initial provider plugin implementation for [go-aws-news] as well as [several of
the provider plugins][go-aws-news-nick].

[go-aws-news]:https://github.com/circa10a/go-aws-news
[go-aws-news-nick]:https://github.com/circa10a/go-aws-news/commits?author=nickshine

{{% /project %}}

{{% project
  title="hugo-book"
  img="images/hugo.png"
  alt="hugo-book theme"
  link="https://github.com/alex-shpak/hugo-book" %}}

[Implemented source editing and last-modified date feature][hugo-book-nick] on this popular
[Hugo theme].

[hugo-book-nick]:https://github.com/alex-shpak/hugo-book/commits?author=nickshine
[hugo theme]:https://themes.gohugo.io/hugo-book/

{{% /project %}}
