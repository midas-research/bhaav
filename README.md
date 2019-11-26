# BHAAV
A dataset of sentences from Hindi stories tagged with different emotion tags developed by

<br>
<p align="center">
  <img src="https://github.com/midas-research/bhaav/blob/master/MIDAS-logo.jpg" alt="MIDAS lab at IIIT-Delhi"  width="60%"/>
  <br>
</p>
<br>

**BHAAV** is the first and largest Hindi text corpus for analyzing emotions that a writer expresses through his characters in a story, as perceived by a narrator/reader. The corpus consists of 20,304 sentences collected from 230 different short stories spanning across 18 genres such as प्रेरणादायक (Inspirational) and रहस्यमयी (Mystery). Each sentence has been annotated into one of the five emotion categories **anger**, **joy**, **suspense**, **sad**, and **neutral**.



This repository contains link to download the data, and information about the corpus.

For more details on how the dataset was created, and baseline models,
please refer to our paper, [BHAAV- A Text Corpus for Emotion Analysis from Hindi Stories](https://arxiv.org/abs/1910.04073)

The dataset can be obtained from https://zenodo.org/record/3457467#.Xd07oy2ZO-t

## Dataset Stats
/***
\begin{table}[htbp]
\centering
\scalebox{0.45}{
\begin{tabular}{|c|c|c|}
\hline
\textbf{Dataset/Genre} & \textbf{Fleiss's Kappa} & \textbf{Krippendorff's alpha} \\ \hline
BHAAV dataset &  0.80241357 & 0.802416004636 \\ \hline
\begin{hindi}आदर्शवादी\end{hindi} (Idealist)
& 0.741594061693 & 0.740462670362\\ \hline
\begin{hindi}प्रेमपरक\end{hindi} (Romantic)
&  0.906633895329 & 0.90659267822 \\ \hline
\begin{hindi}शहरी जीवन \end{hindi} (Urban Life)
& 0.825558745183  & 0.824972237422 \\ \hline
\begin{hindi}शोषक और शोषित वर्ग\end{hindi} (Exploiter and Exploited Class) & 0.798745458224 & 0.797991236844  \\ \hline
\begin{hindi}नीतिपरक\end{hindi} (Moral Stories)
& 0.865927372214 & 0.865857301713 \\ \hline
\begin{hindi}किसान जीवन\end{hindi} (Life of a Farmer)
& 0.885919097027 & 0.886009070648 \\ \hline
\begin{hindi}ऐतिहासिक\end{hindi} (Historical)
& 0.921326884658 & 0.921310220449 \\ \hline
\begin{hindi}प्रेरणादायक\end{hindi} (Inspirational)
& 0.897278304968 & 0.897266011499 \\ \hline
\begin{hindi}देश भक्ति संभंधित\end{hindi} (Patriotic) & 0.991438728869 & 0.991446652425 \\ \hline
\begin{hindi}व्यक्तिगत जीवन की समस्या\end{hindi} (Personal Issues/Problems) & 0.879354980254 & 0.879386098588 \\ \hline
\begin{hindi}रूढ़ि और अंधविश्वास \end{hindi} (Dogmatic and Superstitious) & 1.0 & 1.0 \\ \hline
\begin{hindi}संयुक्त परिवार की समस्या\end{hindi} (Joint Family Problems) & 0.887607633305 & 0.887631947099 \\ \hline
\begin{hindi}रहस्यमयी\end{hindi} (Mystery)
&  0.908185638589 &  0.908330457028\\ \hline
\begin{hindi}यथार्थवादी\end{hindi} (Realistic and Pragmatic)
& 0.912201981538 & 0.912237344469 \\ \hline
\begin{hindi}ग्रामीण जीवन\end{hindi} (Village Life)
& 0.967427620692 & 0.967434538508 \\ \hline
\begin{hindi}उपदेशपरक\end{hindi} (Instructive)
& 0.919704200254 & 0.919700170635 \\ \hline
\begin{hindi}भोगे हुए यथार्थ की कहानी\end{hindi} (Real Stories) & 0.911361226137 & 0.911352174976 \\ \hline
\begin{hindi}समाज सुधारक\end{hindi} (Society and its Reformation) & 0.878218452096 & 0.878149647043 \\ \hline
\end{tabular}}
\caption{\footnotesize Inter-annotator Agreements as measured using Fleiss`s Kappa \cite{fleiss1973equivalence} and Krippendorff`s alpha \cite{krippendorff2011computing} for the entire BHAAV dataset and for each genre.}
\label{agreement-table}
\end{table}
***/
## References

Please cite [[1]](https://arxiv.org/abs/1910.04073) if you found the resources in this repository useful.


[1] Kumar, Y., Mahata, D., Aggarwal, S., Chugh, A., Maheshwari, R., and Shah, R. R. [*BHAAV- A Text Corpus for Emotion Analysis from Hindi Stories*](https://arxiv.org/abs/1910.04073)


```
@article{kumar2019bhaav,
  title={BHAAV-A Text Corpus for Emotion Analysis from Hindi Stories},
  author={Kumar, Yaman and Mahata, Debanjan and Aggarwal, Sagar and Chugh, Anmol and Maheshwari, Rajat and Shah, Rajiv Ratn},
  journal={arXiv preprint arXiv:1910.04073},
  year={2019}
}
```
