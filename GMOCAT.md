
\begin{table*}[!ht]
  \centering
  \renewcommand{\arraystretch}{0.9}
  \caption{The AUC and ACC performance on Student Performance Prediction task on four datasets. The best results are highlighted in bold, while the second-best value is underlined.}
 \setlength{\tabcolsep}{0.2mm}{
     % \begin{tabularx}
     % {\linewidth}{XX|XXXX|XXXX|XXXX|XXXX} \hline
     \begin{tabular}{cc|cccc|cccc|cccc|cccc} \hline
    \toprule
    \toprule
    \multicolumn{2}{c|}{Dataset} & \multicolumn{4}{c|}{Assist09} & \multicolumn{4}{c|}{NIPS-EDU} & \multicolumn{4}{c|}{Assist12} &\multicolumn{4}{c}{Math} \\
    \midrule
    % \multicolumn{2}{c|}{CDM} & \multicolumn{2}{c}{MIRT} & \multicolumn{2}{c|}{NCD} & \multicolumn{2}{c}{MIRT} & \multicolumn{2}{c|}{NCD} & \multicolumn{2}{c}{MIRT} & \multicolumn{2}{c|}{NCD}& \multicolumn{2}{c}{MIRT} & \multicolumn{2}{c}{NCD} \\
    % \multicolumn{2}{c|}{CDM} & \multicolumn{16}{c}{NCD} \\
    % \midrule
    % \multicolumn{2}{c|}{Metric} & \multicolumn{4}{c|}{AUC}      & \multicolumn{4}{c|}{AUC}      & \multicolumn{4}{c|}{AUC} & \multicolumn{4}{c}{AUC} \\
    \multicolumn{2}{c|}{Metric} & \multicolumn{16}{c}{AUC/ACC} \\
    \midrule
    \multicolumn{2}{c|}{Step} & \multicolumn{2}{c|}{5} & \multicolumn{2}{c|}{10} & \multicolumn{2}{c|}{5} & \multicolumn{2}{c|}{10} & \multicolumn{2}{c|}{5} & \multicolumn{2}{c|}{10}& \multicolumn{2}{c|}{5} & \multicolumn{2}{c}{10} \\
    \midrule
    \multirow{3}[6]{*}{Policy} & Random & \multicolumn{2}{c|}{0.6394/0.6024} & \multicolumn{2}{c|}{0.6480/0.6057} & \multicolumn{2}{c|}{0.6851/0.6265} & \multicolumn{2}{c|}{0.7035/0.6305} & \multicolumn{2}{c|}{0.6452/0.7050} & \multicolumn{2}{c|}{0.6488/0.7085} & \multicolumn{2}{c|}{0.7240/0.6577} & \multicolumn{2}{c}{0.7302/0.6733} \\
    \cmidrule{2-18}            & MAAT   & \multicolumn{2}{c|}{0.6431/0.6129} & \multicolumn{2}{c|}{0.6517/0.6170} & \multicolumn{2}{c|}{0.6988/0.6349} & \multicolumn{2}{c|}{0.7226/0.6329} & \multicolumn{2}{c|}{0.6549/0.7120} & \multicolumn{2}{c|}{0.6563/0.7137} & \multicolumn{2}{c|}{0.7262/0.6653} & \multicolumn{2}{c}{0.7425/0.6800} \\
    \cmidrule{2-18}            & BECAT  & \multicolumn{2}{c|}{0.6425/0.6141} & \multicolumn{2}{c|}{0.6522/0.6191} & \multicolumn{2}{c|}{0.7011/0.6404} & \multicolumn{2}{c|}{0.7288/0.6491} & \multicolumn{2}{c|}{0.6589/0.7133} & \multicolumn{2}{c|}{0.6611/0.7172} & \multicolumn{2}{c|}{0.7189/0.6601} & \multicolumn{2}{c}{0.7432/0.6822}\\
    \midrule
    \multirow{2}[6]{*}{Learnable} & BOBCAT& \multicolumn{2}{c|}{0.6419/0.6136}   & 
\multicolumn{2}{c|}{0.6513/0.6213}   & 
\multicolumn{2}{c|}{0.7016/0.6395}   & 
\multicolumn{2}{c|}{0.7268/0.6513}   & 
\multicolumn{2}{c|}{0.6553/0.7125}   & 
\multicolumn{2}{c|}{0.6680/0.7197}   & 
\multicolumn{2}{c|}{0.7211/0.6649}   & 
\multicolumn{2}{c}{0.7453/0.6864}\\
\cmidrule{2-18}          & NCAT  & \multicolumn{2}{c|}{0.6423/0.6184}   & 
\multicolumn{2}{c|}{0.6526/0.6263}   & 
\multicolumn{2}{c|}{0.7053/0.6421}   & 
\multicolumn{2}{c|}{0.7298/0.6533}   & 
\multicolumn{2}{c}{0.6565/0.7154}   & \multicolumn{2}{c|}{0.6653/0.7203}  & \multicolumn{2}{c|}{0.7245/0.6673}   & 
\multicolumn{2}{c}{0.7467/0.6856} \\
\cmidrule{2-18}          & GMOCAT  & \multicolumn{2}{c|}{\underline{0.6443}/\underline{0.6225}}   & 
\multicolumn{2}{c|}{0.6525/0.6283}   & 
\multicolumn{2}{c|}{0.7082/0.6478}   & 
\multicolumn{2}{c|}{0.7314/0.6546}   & 
\multicolumn{2}{c}{0.6633/0.7144}   & \multicolumn{2}{c|}{0.6741/0.7188}  & \multicolumn{2}{c|}{0.0.7278/0.6704}   & 
\multicolumn{2}{c}{0.7524/0.6933} \\
% \cmidrule{2-18}          & GMOCAT & \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}   & 
% \multicolumn{2}{c}{}\\
    \midrule
    \multirow{3}[5]{*}{RECAT} & Random & 
\multicolumn{2}{c|}{0.6428/0.6215}  & 
\multicolumn{2}{c|}{0.6525/0.6322}  & 
\multicolumn{2}{c|}{0.7112/0.6498}  & 
\multicolumn{2}{c|}{0.7356/0.6615}  & 
\multicolumn{2}{c|}{0.6706/0.7158}  & 
\multicolumn{2}{c|}{0.6801/0.7211}  & 
\multicolumn{2}{c|}{0.7339/0.6728}  & 
\multicolumn{2}{c}{0.7514/0.6923}  \\
\cmidrule{2-18}          & MAAT & \multicolumn{2}{c|}{\textbf{0.6485}/\textbf{0.6249}}   & 
\multicolumn{2}{c|}{\underline{0.6530}/\textbf{0.6348}}   & 
\multicolumn{2}{c|}{\underline{0.7131}/\underline{0.6525}}   & 
\multicolumn{2}{c|}{\underline{0.7400}/\textbf{0.6663}}   & 
\multicolumn{2}{c|}{\textbf{0.6711}/\textbf{0.7170}}   & 
\multicolumn{2}{c|}{\underline{0.6805}/\textbf{0.7222}}   & 
\multicolumn{2}{c|}{\underline{0.7345}/\underline{0.6737}}      &
\multicolumn{2}{c}{\underline{0.7562}/\underline{0.6945}} \\
\cmidrule{2-18}          & BECAT& \multicolumn{2}{c|}{0.6436/0.6222}   & 
\multicolumn{2}{c|}{\textbf{0.6564}/\underline{0.6307}}    & 
\multicolumn{2}{c|}{\textbf{0.7197}/\textbf{0.6542}}      & 
\multicolumn{2}{c|}{\textbf{0.7423}/\underline{0.6632}}      & 
\multicolumn{2}{c|}{\underline{0.6709}/\underline{0.7161}}   & 
\multicolumn{2}{c|}{\textbf{0.6815}/\underline{0.7213}} & 
\multicolumn{2}{c|}{\textbf{0.7356}/\textbf{0.6758}}      & 
\multicolumn{2}{c}{\textbf{0.7574}/\textbf{0.6956}} \\\hline 
% \hline    \multicolumn{2}{c|}{Metric} & \multicolumn{4}{c|}{ACC}      & \multicolumn{4}{c|}{ACC}      & \multicolumn{4}{c|}{ACC} & \multicolumn{4}{c}{ACC} \\
% \hline    \multicolumn{2}{c|}{Metric} & \multicolumn{16}{c}{ACC} \\
%     \midrule
%     \multicolumn{2}{c|}{Step} & \multicolumn{2}{c}{5} & \multicolumn{2}{c|}{10} & \multicolumn{2}{c}{5} & \multicolumn{2}{c|}{10} & \multicolumn{2}{c}{5} & \multicolumn{2}{c|}{10} & \multicolumn{2}{c}{5} & \multicolumn{2}{c}{10} \\
%     \midrule
%     \multirow{3}[6]{*}{Static} & Random & \multicolumn{2}{c}{0.6024} & \multicolumn{2}{c}{0.6057} & \multicolumn{2}{c}{0.6265} & \multicolumn{2}{c}{0.6305} & \multicolumn{2}{c}{0.7050} & \multicolumn{2}{c}{0.7085} & \multicolumn{2}{c}{0.6577} & \multicolumn{2}{c}{0.6733} \\
% \cmidrule{2-18}          & MAAT  & \multicolumn{2}{c}{0.6129}   & \multicolumn{2}{c}{0.6170}    & \multicolumn{2}{c}{0.6349}      & \multicolumn{2}{c}{0.6329}      & \multicolumn{2}{c}{0.7120}   & \multicolumn{2}{c}{0.7137}  & \multicolumn{2}{c}{0.6653}      & \multicolumn{2}{c}{0.6800} \\
% \cmidrule{2-18}          & BECAT & \multicolumn{2}{c}{0.6141}   & \multicolumn{2}{c}{0.6191}    & \multicolumn{2}{c}{0.6404}      & \multicolumn{2}{c}{0.6491}      & \multicolumn{2}{c}{0.7133}   & \multicolumn{2}{c}{0.7172} & \multicolumn{2}{c}{0.6601}& \multicolumn{2}{c}{0.6822}\\
%     \midrule
%     \multirow{2}[6]{*}{Learnable} & BOBCAT& 
% \multicolumn{2}{c}{0.6136}   & 
% \multicolumn{2}{c}{0.6213}    & 
% \multicolumn{2}{c}{0.6395}      & 
% \multicolumn{2}{c}{0.6513}      & 
% \multicolumn{2}{c}{0.7125}   & 
% \multicolumn{2}{c}{0.7197}  & 
% \multicolumn{2}{c}{0.6649}      & 
% \multicolumn{2}{c}{0.6864} \\
% \cmidrule{2-18}          & NCAT  & \multicolumn{2}{c}{0.6184}   & 
% \multicolumn{2}{c}{0.6263}    & 
% \multicolumn{2}{c}{0.6421}      & 
% \multicolumn{2}{c}{0.6533}      & 
% \multicolumn{2}{c}{0.7154}   & \multicolumn{2}{c}{0.7203} & \multicolumn{2}{c}{0.6673}      & 
% \multicolumn{2}{c}{0.6856} \\
% % \cmidrule{2-18}          & GMOCAT & \multicolumn{2}{c}{}   & 
% % \multicolumn{2}{c}{}    & 
% % \multicolumn{2}{c}{}      & 
% % \multicolumn{2}{c}{}      & 
% % \multicolumn{2}{c}{}   & 
% % \multicolumn{2}{c}{} & 
% % \multicolumn{2}{c}{}      & 
% % \multicolumn{2}{c}{} \\
%     \midrule
%     \multirow{3}[6]{*}{RECAT} & RECAT-Random & 
%     \multicolumn{2}{c}{0.6215}   & 
%     \multicolumn{2}{c}{0.6322}    & 
%     \multicolumn{2}{c}{0.6498}      & 
%     \multicolumn{2}{c}{0.6615}      & 
%     \multicolumn{2}{c}{0.7158}   & 
%     \multicolumn{2}{c}{0.7211}  & 
%     \multicolumn{2}{c}{0.6728}      & 
%     \multicolumn{2}{c}{0.6923} \\
% \cmidrule{2-18}          & RECAT-MAAT & 
% \multicolumn{2}{c}{\textbf{0.6249}}   & 
% \multicolumn{2}{c}{\textbf{0.6348}}    & 
% \multicolumn{2}{c}{\underline{0.6525}}      & 
% \multicolumn{2}{c}{\textbf{0.6663}}      & 
% \multicolumn{2}{c}{\textbf{0.7170}}   & 
% \multicolumn{2}{c}{\textbf{0.7222}}  & 
% \multicolumn{2}{c}{\underline{0.6737}}      & 
% \multicolumn{2}{c}{\underline{0.6945}} \\
% \cmidrule{2-18}          & RECAT-BECAT & \multicolumn{2}{c}{\underline{0.6222}}   & 
% \multicolumn{2}{c}{\underline{0.6307}}    & 
% \multicolumn{2}{c}{\textbf{0.6542}}      & 
% \multicolumn{2}{c}{\underline{0.6632}}      & 
% \multicolumn{2}{c}{\underline{0.7161}}   & \multicolumn{2}{c}{\underline{0.7213}}   & \multicolumn{2}{c}{\textbf{0.6758}}      & 
% \multicolumn{2}{c}{\textbf{0.6956}}\\
\bottomrule
    \end{tabular}%
       }
  \label{RQ1}%
\end{table*}%

