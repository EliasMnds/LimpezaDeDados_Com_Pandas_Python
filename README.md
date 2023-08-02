# LimpezaDeDados_Com_Pandas_Python

In this notebook is used a dataset from Kaggle: https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube
The main objetive is train the data cleaning process, that is comproved a important step from Data Mining. 

The data cleaning process is important because of the errors associated with the data
collection process. Several sources of missing entries and errors may arise during the data
collection process. Some examples are as follows:
1. Some data collection technologies, such as sensors, are inherently inaccurate because
of the hardware limitations associated with collection and transmission. Sometimes
sensors may drop readings because of hardware failure or battery exhaustion.
2. Data collected using scanning technologies may have errors associated with it because
optical character recognition techniques are far from perfect. Furthermore, speech-to-
text data is also prone to errors.
3. Users may not want to specify their information for privacy reasons, or they may
specify incorrect values intentionally. For example, it has often been observed that
users sometimes specify their birthday incorrectly on automated registration sites
such as those of social networks. In some cases, users may choose to leave several
ﬁelds empty.
4. A signiﬁcant amount of data is created manually. Manual errors are common during
data entry.
5. The entity in charge of data collection may not collect certain ﬁelds for some records,
if it is too costly. Therefore, records may be incompletely speciﬁed.

The aforementioned issues may be a signiﬁcant source of inaccuracy for data mining appli-
cations. Methods are needed to remove or correct missing and erroneous entries from the
data. There are several important aspects of data cleaning:
1. Handling missing entries: Many entries in the data may remain unspeciﬁed because of
weaknesses in data collection or the inherent nature of the data. Such missing entries
may need to be estimated. The process of estimating missing entries is also referred
to as imputation.
2. Handling incorrect entries: In cases where the same information is available from
multiple sources, inconsistencies may be detected. Such inconsistencies can be removed
as a part of the analytical process. Another method for detecting the incorrect entries
is to use domain-speciﬁc knowledge about what is already known about the data.
For example, if a person’s height is listed as 6 m, it is most likely incorrect. More
generally, data points that are inconsistent with the remaining data distribution are
often noisy. Such data points are referred to as outliers. It is, however, dangerous
to assume that such data points are always caused by errors. For example, a record
representing credit card fraud is likely to be inconsistent with respect to the patterns
in most of the (normal) data but should not be removed as “incorrect” data.
4. Scaling and normalization: The data may often be expressed in very diﬀerent scales
(e.g., age and salary). This may result in some features being inadvertently weighted
too much so that the other features are implicitly ignored. Therefore, it is important
to normalize the diﬀerent features.

Data Mining : The Text Book ( Charu C. Aggarwal )
