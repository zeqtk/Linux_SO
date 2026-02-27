<<<<<<< HEAD
#
Linux_SO
=======
# Linux_SO

*Uma visão das características das distros linux usando o mariadb*

*Exemplo:*

CREATE VIEW V_LINUX AS SELECT D.NOME,D.TIPO,D.BASE,D.FOCO, IFNULL(D.DESKTOP,'***') AS DESKTOP,D.GERENCIADOR,D.LANCAMENTO,C.DESENVOLVEDOR FROM DISTRO D INNER JOIN CRIADOR C ON D.IDDISTRO = C.ID_DISTRO;

+--------------+-----------------+---------------+-------------------------+----------+--------------+------------+----------------------+
| NOME         | TIPO            | BASE          | FOCO                    | DESKTOP  | GERENCIADOR  | LANCAMENTO | DESENVOLVEDOR        |
+--------------+-----------------+---------------+-------------------------+----------+--------------+------------+----------------------+
| UBUNTU       | LTS             | DEBIAN        | INICIANTE/GERAL         | GNOME    | APT          |       2004 | MARK SHUTTLEWORTH    |
| FEDORA       | BLEEDING EDGE   | RED HAT       | TECNOLOGIA              | GNOME    | DNF          |       2003 | RED HAT              |
| LINUX MINT   | LTS             | UBUNTU/DEBIAN | INICIANTES              | CINNAMON | APT          |       2006 | CLEMENT LEFEBVRE     |
| MANJARO      | ROLLING RELEASE | ARCH LINUX    | USO GERAL               | XFCE/KDE | PACMAN/PAMAC |       2011 | FILIPE MÜLLER        |
| POP!_OS      | LTS             | UBUNTU        | PRODUTIVIDADE/JOGOS     | COSMIC   | APT          |       2017 | SYSTEM76             |
| VOID LINUX   | ROLLING RELEASE | INDEPENDENTE  | LEVEZA                  | XFCE     | XBPS         |       2008 | JUAN ROMERO PARDINES |
| ALPINE LINUX | LTS             | INDEPENDENTE  | SIMPLICIDADE/SEGURANÇA  | ***      | APK          |       2005 | COPA NATANEL         |
| SLACKWARE    | FIXED-RELEASE   | SLS           | KISS                    | XFCE     | SLACKPKG     |       1993 | PATRICK VOLKERDING   |
+--------------+-----------------+---------------+-------------------------+----------+--------------+------------+----------------------+
>>>>>>> 3a05146a518acb8fdaf4d755d7d92730fe86dc1a
