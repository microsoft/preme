# [PREME: Preference-based Meeting Exploration through an Interactive Questionnaire](https://arxiv.org/pdf/2205.02370)
This repo contains [the annotated data for PREME paper(https://github.com/microsoft/preme/blob/main/data.tsv).

The data contains 1000 annotated questions with their ```subject``` and ```aspect``` or ```what was said about  the subjest``` by 2 annotators. 

The format of the annotated data is as follows where the query comes with a json file including:
```
- subject1
- subject2  (if exists) 
- person (if exists)
```

For example:
```
Query<\t>data
 How does the new system work with HMRC?  {"Subject1":"new system","Subject2":"HMRC","What-Was-Said-About-the-Subject":"work with"} # Annotators 1 
 How does the new system work with HMRC?	{"Subject1":"HMRC","What-Was-Said-About-the-Subject":"new system work"} # Annotator 2
 Which energy source is worth looking into?	{"Subject1":"energy source","What-Was-Said-About-the-Subject":"worth looking into"} # Annotators 1 
 Which energy source is worth looking into?	{"Subject1":"energy source","What-Was-Said-About-the-Subject":"worth looking into"} # Annotator 2
```
 
For more information about the data, we encourage the read the [PREME paper](https://arxiv.org/abs/2205.02370) published in EACL2023. 
## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Reference:

If you used PREME data in your work, please consider citing the following paper:
```
@@inproceedings{arabzadeh2022preme,
      title={PREME: Preference-based Meeting Exploration through an Interactive Questionnaire}, 
      author={Negar Arabzadeh and Ali Ahmadvand and Julia Kiseleva and Yang Liu and Ahmed Hassan Awadallah and Ming Zhong and Milad Shokouhi},
      year={2023},
      booktitle={EACL}
}
```
