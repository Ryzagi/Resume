\documentclass{resume}

\begin{document}

\fontfamily{ppl}\selectfont

\noindent
\begin{tabularx}{\linewidth}{@{}m{\textwidth} m{0.2\textwidth}@{}}
{
    \Large{Vladislav Ryzhov} \newline
    \small{
        \clink{
            \href{mailto:vladislavrzhv@gmail.com}{vladislavrzhv@gmail.com}
            \textbf{·} 
            \href{https://github.com/ryzagi}{Github, Telegram, Slack ODS.ai:@Ryzagi}
} \textbf{·} 
            {\fontdimen2\font=0.75ex Mobile +7 977 759 90 69} 
            \textbf{·} 
            %\clink{
            %\href{}{Github, Telegram, Slack ODS.ai:@Ryzagi}}
        } \newline
        Moscow, Russia
    }
 & 
{
    
}
\end{tabularx}
\begin{center}
\begin{tabularx}{\linewidth}{@{}*{2}{X}@{}}
% left side %
{
    \csection{ОПЫТ}{\small
        \begin{itemize}
            % item 1 %
            \item \frcontent{Schlumberger Moscow Research}{Data Scientist}{Разработаны нейронные сети для прогнозирования параметров потока многофазного флюида на основе измерения акустического шума (временных рядов). Решены задачи регрессии и классификации. }{Апрель 2021 - Июль 2022}
            % item 2 %
        \end{itemize}
    }
    \csection{ХАКАТОНЫ}{\small
        \begin{itemize}
            % item 1 %
            \item \frcontent{Хакатон Института океанологии РАН/ЦМИ МГУ, 1 место}{ ML исследователь - Москва, Россия.}{Данные для задачи собраны в экспедиции АИ-58 в Северном Ледовитом океане. Аппроксимировали поток коротковолновой солнечной радиации на поверхности океана по фотографиям облачности(по их статистикам).}{}
            \item \frcontent{Хакатон Цифровой Прорыв, 2 место}{Python программист , ML исследователь - Казань, Россия.}{Был руководителем команды университета, разработали сервис для обнаружения дефектов на железнодорожных путях по данным с датчиков мобильных устройств, включая классификационную модель и мобильное приложение.  }{}
            % item 2 %
            \item \frcontent{Индустриальный Хакатон КРОК PROHACK, 3 место}{Python программист , ML исследователь - Москва, Россия.}{Создали MVP - приложение для отслеживания дефектов в батончиках TWIX.}{}
            % item 3 %
            \item \frcontent{Роснефть, Хакатоны Вузов Страны, 4 место}{Python программист , ML исследователь - Москва, Россия.}{Задача кластеризации и регрессии по данным временных рядов (каротажи скважин).}{}
            
        \end{itemize}
    }
    \csection{ОБРАЗОВАНИЕ}{\small
        \begin{itemize}
            % item 1 %
            \item \frcontent{09.03.03. Прикладная информатика, бакалавриат. Ср.Балл: 4.95 / 5.0}{МГРИ-РГГРУ }{Тема диплома: Разработка нейронной сети для определения параметров потока многофазного флюида на основе акустических измерений. {\href{https://istina.msu.ru/publications/article/458191933/}{ссылка}}}
           {{Авг. 2018 - Июнь 2022}}
            \item \frcontent{Производственная практика, Сколтех (Skoltech) }{Занимался теоретическим моделированием эффективной теплопроводности пород-коллекторов на базе Центра добычи углеводородов Сколтеха.}{}{}
            \item \frcontent{Языки }{Английский (B2+), Русский (родной).}{}{}
        \end{itemize}
    }
    \csection{СЕРТИФИКАТЫ}{\small
        \begin{itemize}
            
            \item \frcontent{Профессиональная Сертификация TensorFlow}
            {\href{https://coursera.org/share/249817f9608e1dc1c6fc4b4ad9d7ca1c}{ссылка}}{ Лоуренс Морони Lead  Google, Проф. Эндрю Ын  DeepLearning.ai }{}{}
            % item 1 %
            \item \frcontent{Специализация Глубокое Обучения}
            {\href{https://coursera.org/share/6b75d3292fe59f37a6b1ed45f2f0e6b2}{ссылка}}
            {Проф. Эндрю Ын, DeepLearning.ai}{}{}
            % item 2 %
            \item \frcontent{Специализация Генеративно-состязательные сети (GANs)}
            {\href{https://coursera.org/share/e46914198643b72fb78702655890fd78}{ссылка}}
            {Шэрон Чжоу, DeepLearning.ai}{}{}
            % item 3 %
           
        \end{itemize}
    }
} 
% end left side %
& 
% right side %
{
    \csection{НАВЫКИ}{\small
        \begin{itemize}
            \item \textbf{Технологии} \newline
            {\footnotesize  Python, базовый SQL, базовый MongoDB }{}{}
            \item \textbf{Машинное обучение } \newline
            {\footnotesize Scikit-learn, LightGBM, XGBoost, Numpy, Matplotlib, Plotly, Scipy, Pandas, Librosa, etc}
            
            \item \textbf{Глубокое обучение} \newline
            {\footnotesize  TensorFlow, Keras, PyTorch }
            
        \end{itemize}
    }
    \csection{ИССЛЕДОВАНИЯ}{\small
        \begin{itemize}
            \item \frcontent{Обнаружение сейсмических горизонтов с помощью CNN}
            {\href{https://www.elibrary.ru/item.asp?id=45743921}{ссылка}}
            {Тезис о сегментации сейсмических горизонтов с помощью сверточной нейронной сети (CNN) на срезах сейсмического куба.}{}{Python, PyTorch}
            
            \item \frcontent{Нейронная сеть для прогнозирования землетрясений по временным рядам сейсмических данных }
            {\href{https://www.elibrary.ru/item.asp?id=45686828}{ссылка}}
            {Тезис о прогнозировании сейсмических временных рядов с помощью комбинированной нейронной сети. Мой метод был апробирован на данных Камчатки и Командорских островов.}{}{Python, TensorFlow, Keras}
            \item \frcontent{Классификация фаций с использованием различных методов машинного обучения}
            {\href{https://github.com/Ryzagi/Facies_classification}{ссылка}}
            {Исследовательская работа о классификации фаций скважин с использованием различных методов машинного обучения на данных каротажей (временных рядов). Признаки включают пять из каротажных измерений и две ограничивающие геологические переменные, которые получены по геологическим исследованиям. }{}{Python, Scikit-learn, PyTorch }
            \item \frcontent{Прогнозирование активности солнечных пятен}{Проект о прогнозировании активности солнечных пятен по временным рядам. }{}{Python, Tensorflow, Keras }
            
        \end{itemize}
    }
    \csection{ДРУГИЕ ДОСТИЖЕНИЯ}{\small
        \begin{itemize}
            
            \item \frcontent{Благодарственное письмо от вуза}{Получил грамоту за активное участие в общественной жизни университета и успешную реализацию молодежных инновационных проектов. }{}{}
            \item \frcontent{Робототехника}{Сертификат о прохождении курса робототехники, Школьная Международная Конференция - проект Умная теплица, 1 место.}{}{}
        \end{itemize}
    }
    \csection{ХОББИ И ИНТЕРЕСЫ}{\small
        \vspace{0.42cm}
        \begin{tabularx}{\linewidth}{@{}*{4}{>{\centering\arraybackslash}X}@{}}
            
            {\footnotesize Математика} & {\footnotesize Спорт} & {\footnotesize Временные ряды } & {\footnotesize DL}
        \end{tabularx}
    }
}
\end{tabularx}
\end{center}
\end{document}
