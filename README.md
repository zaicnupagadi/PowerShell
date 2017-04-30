![polish_powershell_group_pposh_logo2](https://cloud.githubusercontent.com/assets/19157221/25561611/52b4cd36-2d70-11e7-8c8f-907dfd947524.png)

# Introduction do PowerShell DSC

DSC was first topic covered by me on the first Polish PowerShell User Group meeting :) 

## Thank you all for joining!

On the first meeting I have highlited what it is, how to install it and what are the capabilities.

I would like to continue with subject of the DSC and focus on aspects like HA cluster for HTTPS pull server, building advanced pull servers on windows core, present available resources, using Linux as authoring workstation (also covering  PowerShell on Linux thing), etc.

At the end of the path I would like us to go through complete roadmap of DSC available features and configuration options so we together have it sorted out when comes to implement it in our environment.

All of this would be documented on this PPOSH GitHub and my private blog https://paweljarosz.wordpress.com

This resource contains:
1. Presentation from the first PPOSH meeting
2. Instructions how to build first HTTPS DSC Pull Server
3. Instructions how to apply basic configuration on Windows and Linux clients

## Creating a test lab

To create a test lab for this I would suggest having 3 machines:

1. LABDSCPS01 – W2016 / DSC HTTPS Pull Server (192.168.0.33)
2. LABDC01 – W2016 / DC / DSC Windows client (192.168.0.31)
3. LABCENTOS01 – Centos 7 / DSC Linux client (192.168.0.32)

# This is an h1 tag
```powershell
Write-Host "Siemka"
$p= "Takie Tam"
ForEach ($a in $p) {
Write-Verbose "Bla"
}
```

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
   As Kanye West said:

> We're living the future so
> the present is our past.

I think you should use an
`<addr>` element here instead.

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
