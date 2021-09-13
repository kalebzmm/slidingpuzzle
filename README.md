### slidingpuzzle 

# O problema

<img alt="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANMAAADTCAIAAACUZbGOAAAABGdBTUEAAK/INwWK6QAAABl0RVh0U29mdHdhcmUAQWRvYmUgSW1hZ2VSZWFkeXHJZTwAACFySURBVHja7F0HcFXV1j4iioSWSBUSCEWkJIAFCMhN6EHFMoCAhG40qJSQAUal2FCkOQhGihDKKGhUUBBFIAGSCEFkUEFE6RAUiYghEPGpv//n/SbrnYcYuYfcc/Y92Wve3Hduway197dX22uvfdWff/5paNJkL6WkLCuN/zt6JEePhSabqZQeAk0aeZo08jRp0sjTpJGnSZNGnqYAp9L/9EV43TA9OpqunI4cPq51niZtbTVpa2tZWypO4i1o/p3lX+s8TdraatKkkadJI0+TjjCKpDrhoQsWLEhNTU1LS+Mn11133YULF6666ipHBPB4PPHx8QMGDLjMWi/Nv7P8W0cexE5KSjp//jyer7322v946SovOSJ5RkZGdnY2OIlqfbvmX33+rSMPq41iBwUFFRQUXHPNNb///vufXnJKb2Pok5OTL1Nyzb+z/FtHHpU8xM7Lyytd+q9/joEoV66cU2JfffXVpUqVysrK0vwHBP/WkUclj9UGsc+cORMSEgKx4WfgQ0ck/z8vaf4DiH/ryIN2hZLHA8SGzNd5ycEoyVcvR/PvLP8WsyoQEtoVvgW9DQZWDooNbQ8X5/JXvObfWf6t6zwG8PhjVPJccNC3TsVWf/zxB+zO5Y++5t9Z/q0jj6qVkZQgvWh9C+awMugQ0CmGvcC//fXXX2E1sILNP7MgPBSAX/nHj/kt+MezmUnhWX6jGv+//fYbBlk4xyueyTOYx+DjH+IBr3jmj/3K/xX5eRb8QowRpOWQUTlD2jJlynDOuG7wA8vg8zf98ssveC1btqy41Zw2mULaHcwBl5Y6RCSBVcYBmAKOMxkW4HL9W4CdZbJjmGTCRHOIfwBQmgVWsOEBuMWsUASq7VKFJDyLFpEP1SFZzOBNACeYuwiCdq58O5BHrSYSEn80T1R78lbBmQNL3CTA8sArVVpBQQFkAfNcRfgQ2k58CaUIfIJ/ODbgltaZcyHf0iiZf+Ae5NHJEMUGyeUTvNJL4LdOucn/mj8z62zDm8ilCyWcUxYFmcdoX+sl8ckw+HwLwIFnrBb5gZ06z+86BlEPhOH0YGFRVE4V317jJQwHVYtqM8eFAfbEj4ZEBJn447J5qiDyhCuMNrWyKGY+40N8ddGP3aDzEPNjJWGS8AB9fv78+S+//HLjxo2Qtly5ci1btmzSpEnNmjVh1OgwqWZwMTfUBAz9Dh8+vHPnzn379uGr0NBQ8F+/fv0KFSoITFUzuGAbSwVc0bE5duzYjh07MAV4btasGfivXbs2vvrdS3ZmpP0+TEw1QSRgbtasWS+//HJubq5RWGeBh2rVqj388MNPPPEETBimVkFXj5pg27ZtTz31VFpaGhO58m1ERMSkSZN69epFmCqo9qCYsXJycnKmTZu2aNEiOKkcZEwNxvzBBx8cN24cVpHNOru0DWuOWZXhw4cvWbJEonqAjOHtqVOnpk+fvmrVqj179tgZ1V8m0aR++umnd91115kzZzhhkhjD26+++qp///6YzgceeADIU3DlgNWff/757rvvhqojz5JewNTMmTNny5YtUIRYTvRfXeLnUb1NnDgRsMOsQLEDdmXLlmXAS28Xlhfz9+STTyqoMKjG+vXrd/bsWeZdAcTGjRt36NCBouEHmL/4+Pjjx48rCDsu/pkzZxJ2tKdAGNc/0IZv9+7dO2LECHxoDnvdgDwA69VXX2UYAZ8DjgXMLswWLG+dOnWoEfGzpUuXWsuG+5tWr1596NAhrhMgb/bs2bt37/7444/h7WEhMcIF51AeCoa3YC8/Pz85OZmrAnMRHR29cOHC1NTUVq1awdUG4MD8Bx98gFc70/h2+CUZGRk//fQTHsqXL//LL78AYe3bt8dbqA1M1ZgxYwi47777Dr/s2LGjak5ednY2+ISeBvM1atQYNmwYTRWWUN++fTGL+ArWFkpFwfAWKnnDhg3nzp3DIAcHB8Pszps3DzobX91yyy1169bFAyIkDD4MblRUlG0i2JFV+frrrxn9Qf5atWoBdkzjQUjMIje8sSLtdDJ80hngsGLFioAddDMiWfkKgKtXrx5kAewgIHfYFAyPwNv48eO7d+8eGRl58803A3aI9jAv4eHhwCV+gHmRtIursiqDBw9u2LBhlSpVdu3axept7tLiAdYKYuMtPsf8Ic5VMDBs0aIFnDzWI8ElAsKAOUoBdUJFAimgQgwlKTY2tmvXrqwMoCfHGmZMh7g3mB3g0lXWFm4cFEa3bt2wnm677TbmxqAnoEugQuBecF1iOqtWrRoREaHatAFtd955Z0xMTGZmpuEtPYcz/uKLL2Kq8Lpt2zaqOjgSEyZM4B6Uajqb6WIIAsARW3iGq/roo4+KXoTPU7lyZTvzkX7/M4AXXVcpwmFNDvN5Tz/9tFG4DfXII48oqDAYDMIfhwOak5OTl5e3aNGilJQULB6pyoSqRsABLCqYFQJLHHbAjg/gGXoai0RANnDgwNGjRxum0gE3+HmsgGLQR1NLFOLzUaNG7dy5k1MLhQddoiDyaI/gKu3Zswc6m4kVioMphNkNDQ1FCNK8eXMFYcfUHT0Zo7CUBgMO2EEKarh+/fotWbKECsLOCMnvyGNlGKcKhonrDJ8kJCQgyIJtotp48803oTPUzOeB7e+//75Ro0ZpaWngnPaUguArhO3NmjVbvXo1XQsFk3lgEtFbfn4+1jyeDx06JPxjXpYvX444CeNPSd2DPGoIqnFR70OHDoXNMgoL8t544w2Px6PmzDEM79KlyzfffMMqPYSHsK3p6en9+/eHewd1Ait23333rVu3zqkDYEXrPLAtOWQ8A4uLFy9eu3YtXB1YHohw+PDhhx566P3335dKSjf4edxr4rE8qH1g67HHHlu6dCnTY3j7zjvv3HPPPTRVau57Pv/880ePHqWGwwrZtGkTSwmjoqIQs0+aNIm1HvhZp06dVLO53GXm1gs9hPDw8MGDBxvefGr16tXhXuNbiDB27FhEwbYVDdhhbZkS4wNgt3DhQrzFLMK8Ira99957OSjKlgvAHknVMbwi+qk8enj//ffjlfY3KyvrxIkTCuYjmcPCM8IjAgvi8MRuz5498ZY7MbDCp06dco/OMwprJ6HYhw0bhqiQKrBSpUpwmyIiIphhwrqUVJ9qk8cNWVYWMvsvxZVhYWEUh2ts37590CiqxbZr1qzZvn072AO2oNigp2FwuEuLwA5LizWUeLt///7atWu7B3mcKkSyUB6E4A033ABtFxkZSbPF+FfB4jxzYoLPUBvCJ+N0wo7OQ0hIiIJ+alJS0oEDB8gzgvS5c+fKHvSnn36KkYd0dLhdlVUh7N577z14tUxmMnWHUCsjIwN+Ol5hp+Cz45XbOKp56E2aNOGRHzzPmjVLQnW8vv3224QmYIfX2267TcGV07p1a5ZrgN59913oP1aJQyKIw5Q+vqpcuTL3092j8yDhww8/TKtK5QGvXMJeKRHFz2B/7RT+Mpnv3r37F198YXg3nRBeIDCfPXs2lBxio5EjRzIwglw9evRQEHYY4SFDhqxcuZIjn5ubixEePnw41PO8efPgSHD8EeHS53MV8mBkocwYAFJ+HtbiK08wcBtXTWs7ZswYLIns7GyK8Prrr0PVmU/VQ+HVqVMnMTFRzbNziLgRCb311lvgH+MMqM2YMcMobJTBZd+oUSPE5rYyZoO1onsnS9AoPK8g7gVjCzWzKmAyODh42bJlsFlkkofVaX+Z9Iedmjp1qp0lRr7Sa6+9BvDxTMnZs2cRXgB/WDwsTmnbti3coSpVqthZH2lHVmXbtm1YbZIogs3i1g2TTEzy0flllxrVwgu8ImJdv379s88+Gxoayt0nuk2wufHx8VCHffr0wc8wqQrCjp7cUi/VrFnT8J4XxphjaurVq/fcc8/Bya5Vq5bNK9+OvwTfAkJKHQcsL7wKfsUMM40UwsZKlSopGGFATwB/mJXHH3984sSJ+/fvP3nyJFZOtWrVmjZtKnJBlooVKyqIPGpiDDLUXr9+/Y4dO3bkyBGYXawinvpzpC+HHXsYPHhHnQc7RdixboIfsiAesLPWUcbfOpuxEdU2nht4idOJCB2qGmzLJoFqREhx/LmEADhoOGYoIRTUNr+VVgousbbmFgJyTIEJPJ5AMSfMFGznw1oPzg2cAXNfIkwVYAcLS42oZi8iKdEwCiu+qOQoBWAnGxv0fNzj5zFXJGpfztsxnmXqnEtNzdiWug1zw5Z1bIfN2AKiYcHAwpqPEipIPFcry54eqrSWg6mRxLLSsS3b2OCVLqoIU7TBEn1wkWIg/syr0zIy/MS/zAcfeHDhoviD/x1ry8bf/AtjwjajcnPzK+5EX+HK9DvyYHfYEoU98Bxf0FKkqfkPCP6vKMKQrI/0WpRmgI5EAL5aOs2/s/xbRB6jATYGYL0Go1en/GvKfPklmZp/Z/m3bm3lFA87GcqhCgcjAOalNf8Bwf8VxbYUlWqWRzidTSgwRtP8Bwr/1pEHPR8SEiI7Xc6mQnhOwqfrlzT/zvJv0c/zeDyZmZm894h/lWU2Tm2Wc9wjIyM1/wHBv3Wdl5CQwAfuQLAHm1FYwWE/MS+amJio+Q8I/q0jLy4ubsWKFdHR0TyLIJd4OKXtoQOWL1/eu3dvzX9A8P/f0ASwveRtzOF1w/hw5PBxIwBJ868y/2np6aUMTZoccRD1EGjSyNNUgujfsypisAOUNP9a52nSpJGnSX1rq7MSmn9/OAla52nS1laTRp4mTRp5mjTyNGnSyNMU6ORzZWid8NAFCxakpqampaXxE15I4lRlosfjiY+PHzBgwCUrbjT/qvFvHXkQOykpiaXYrIZlQaxTkmdkZGRnZ4OTqNa3a/7V59868rDaKHZQUFBBQQG7UrA81Sm9jaFPTk6+TMk1/87ybx15VPIQOy8vj/0oMBAWDoAUF/HYX1ZWluY/IPi3jjwqed6mwHMoEJtt8ByRnOcANP8BxL915PESEjxAbLb3su3imEuSr16O5t9Z/i1mVdjWGb4FvQ25adNBbc8G85r/gODfus5jAM9mcrLg7O++JsQmkD71YtL8O8i/deRRtTKSEqQXoW+LuNkH/xH2cuQrL0azsHp8aurhK/8UQX7AxuLs3cSGr9RAvMPX2vT7m/9/Mtn859IcQz7xK//Wra3Pf8B7dQ67Uv59EKX/JruIKnhLJ+8B5G2ImBt2pSXIZL4ZY6rQzc6nMIVHxNme2/jf7q42kB27ZzyJfslFKdc4WV46/iZpHVymTBlefE21R1VHnjlhcqtJAIGPC4ZGyea7Nu34S5gnafLKViBydZi57x/nUrXpYRMJQEruiuEdMmRYcEnlraDOLkIuMbUCODvT0XYgT+7KkRliHy4xT3jg5wreAcRlA0jRkyPmpD0yOGe/YvzMzqvYi8sLoji8VYsN+WxjwL6Z5g6P2Tei/sPMBQUFKTtDZtdHlBxARssLEyzuuZ1XsRdXEo6JQM4I04S2gc8+5NGfECEXLVqUm5sL8IWFhQ0dOtQo7Iap2gyJGqYbBM6//PLL7Ozs77//Pjg4OCoqKjIyEg+0s5bDQ0do9+7deXl5LDjweDxm0+Qq5NHIcnrOnDnzzDPP/PDDD3gbGxsbFxfHC5zUpIKCAmhlrIqtW7dOnjz5o48+Mgqvq8TDzTffnJyc3KZNm8CC3cmTJ++///79+/dDqUOWNWvWdOvWzc7Fb4efR2eCES79CchM2NHJIOzUvL0JzNMZgJKOjo4G7PiWveswZ7t27WrXrt1nn32mLOzoT3OdYLQZRrzwwgsHDhxgKzR8RVfBVXd6c0nRmYDOy8/PT0hIyMzMDBTdwKunAK9x48ZhCjFDUIGsDWHYCyDCW+rRo4fcOK+gS0clDYaxyPF2w4YN8+fPp/8jjR8l4eAS5Ench4e9e/fGxMQsXrw4gDxxYAvASkxMhIdgeDevmjVrNm3atC1bttx9992YyAIvwXitXLlSTRGIJyCMOXBYm2HDhuEtr9SSaM/mTt92+HlYTJiYpUuXTpkyhbcpM6QPlOzD0aNHEVWA7UqVKsFaAWH169fHVzC+ISEhmC0gD7O4fv163nKr4OKR21rwOnXq1EOHDvFzIo8ZLrfdMkq/GxYWGp6fYJICKPsFVgG1c+fOYWIQCT7++OPh4eFimF5++WX45q1bt8bS6tu3r5oiQDETZPAcUlJSZs2axetceI2ltPmGpHZGGH5HHiSR4kEWcPfu3bthw4YTJkwIFORlZGTIPZS33HIL03j8duDAgb169VI5H8kcKvVZbm7upEmTWJnRpEkTOD9SRs8kuatuGWVgwWkD7GBwlyxZEljp/rNnz/Kykb/OuURFYXrwSXp6OuJcOH+AHTSicQXVuf4ef8YQUNjDhw8/ceIEDCvMzowZMxAtyS2VcgGse6wtK4iAuU6dOi1atCg0NFSWYKBEGACZbFRgzu644w64dFTn+LZ79+5z587lReUK3s/LwjOgKisrKzU1FZ8gMB80aBCk4Pqnz81yITvvlPf7n2HcxMnj/EliL1CIpQAMz+vVqwcNxyCRaZQPP/zwpptumjNnzpAhQxy/COqS3g5eT506NXToUIKsevXqkydPpuZjnSk9PM6Ue6ytGFzzFcVOFdBaWzmYLe6p44E7tiw3lJvH8Dpq1KgffvhBQbmYQH7kkUdOnz7N3Oq8efMYkhN2LNfAW5vzkaVsUxtmS6SgVSrCQ5d6YzhGmKdGjRqNHj36ueeeu/HGGzGFhjfJxwy5gnKB+TfffHPt2rXMm4DJLl26yLcMabmoLNdUq448o7BcJbCQx30Lcg6FB/cIE/nSSy+NHz9+3759d955J2cXRu3999938Lj1PxHi2bFjx0KfAVWtWrV65pln+Dm0eMWKFbmZRgGBQjv5L22Dzggg2/p3ghmCY8SCDug2+OaNGzc2CrekJk2aBMDB8+NbePEej0cp/hHV5eTkYGGUKVMGS6VPnz5AIZ08ROjXeAnx35gxY6pUqYKvNm3a5BLkBToBUk2bNj148CAzsZgeljhwM6phw4aAHXQG1KG1a15t0NksogaBT4R6soFE347u3eeff26zwrYjn2cUbh2aK5MDyNqydo0Zii+++AKwY6oCM/fTTz/hKwk7FOQf+kzOw0pIIQk8icQvOszmQp1nBmKgWNuePXvCGJHzyZMnd+7cuVmzZnSV5s6di/mT49aqmVpQgwYNYmJisDbKly8vVcfgFuDbsmWLKD9IBLfPhZWh4u0xGcGAEQE/BkIOAcnBVdUmr3bt2u3bt9+8eTOPNMNPj4uLq1Wr1vbt29evXy/nnOPj4xWMnIZ46e+fY8C5n8s93GnTpmFF2Rp0+/sP8LCtaHVuTkuSRQ4OUvkrCDsuhtmzZ3fq1AlxIm9OT0lJ4YTJz2rWrJmYmBhA4ZSc9KPaY/WenQXxdtTniWKTenEe/JFsmWHaXlQwH4YYIjIycuPGjcHBwVhC58+fZ9KfexuQBZ+vXLkSgUggRvF0T2UPzT0RhvkILTUffF74HOLM4oE77s42RCqCf+7JRkRE7Nixo3///kFBQSwxJPP9+vXbs2dPixYt6MIHCuAY6hqFJ4jhCHIb2j3WlrtP3J9hcSJmbsSIEWPHjuUKY5ICigSzqObZM26aYZ7grS9evHj+/Plbt26Fhg4LC6tfvz69JapGYjQgCEP9448/chXR26OM7kGe9CUxq0BKSP+P+QhW7CjoJ5FhacrJ4rwOHToYpmZFRF4AwY5+DmGHAWcNJabAzuNzpWxYW+yfAKkgJ49Gmzut8FW21xTUeczE0g2FOPn5+UZhswS65/ATAqvi0PjfE+wy/nbm8+zIAtCHFanwVspF+ZUc/1YwKwF9BibFDcDbChUqyLKRsnhq8QCq/uIGBlMKFEH1WhUoLaaCzEApesQlpcLZMlew8flKFhz/m5cfnfjKP9uWCXuMxOUfSqcis+ZQiv+izZFh6npjzcn2lX/ryEP4BhYRFiiyX8T16lPPTc2/g/xfUYQhsbccpOODI5Kb+6Bp/gOCf4vIY+4eC47LTkI8p6rAKfPlW2rNv7P8W7e2PBtHp5vHRiRQcIRYW3/5KVDNv7P8X1FsS1HlFILjx158LYzT/DvLv3XkQc+HhITwPgbD6dJ2puB9un5J8+8s/xb9PI/Hk5mZyXuPpDECi8Ud9HAjIyM1/wHBv3Wdl5CQwAf28IKmlaoTR4gn+xMTEzX/AcG/deTFxcWtWLEiOjqa3R5kQ8IpbQ8dsHz58t69e2v+A4L//4YmgO0lb2MOrxvGhyOHjxsBSJp/lflPS08vZWjS5IiDqIdAk0aeJo08TZo08jS5kv49kyxBSoCS5l/rPE2aNPI0qW9tdSZW8+8PJ0HrPE3a2mrSyNOkSSNPU0mNMC6iOuGhCxYsSE1NTUtL4ydyrYIjAng8nvj4+AEDBlyy4sZ95Jrx9xl5EDspKYml2KyGZUGsU5JnZGRkZ2f/dS9U69tLAvJcM/4+Iw+rjWLz+jy2vpLrBhwhDH1ycnIJQZ5rxt9n5FHJQ+y8vDy2esBAWDgAUlzEY39ZWVklxD1yzfhb6TEA1YrVBrF5DgViw8+wsw2RmdS8YdGv5I7xt4I8thjHA8SGzNd5ycGZCKyL1IrFurlg/H3OqkBINnemtyEN+R3U9nLfQ0kg14y/zzqPATz+GJU8F5zNzZ3NxDtuAqhB8RWSa8bfZ+RRtV50ZUwR+laO5bHxjNx7wcuc5AZz6fxqgezsK+04+Tr+RmFLfsKUzxx2+mdyGYTlA5TWxt/vexjSdMPc/Z6XIxqF3QJ546D8RlPxRgAEqLn/JLuesW2rXHTtwltGKbMsMqOw9RU7J7PhsLl5qKbinODCxj8Yf8n5yTiLOuDFJK5CHpvxmtWyNLbG+qODIpqvRIWo9hAgJc2mMMJshkzDyjXPwScoXXWbPH0IqDcaWYJPelwSarzQXMHLMNyBPFF78POILaZ/JS5xxFG26Q4guhe0qnK/oJhdOshyE5em4rW27KwoQQlb7skUQAsSiDZvwfn9JhZosrVr11aqVIl5dip5ue5XFCHvoImJiVHw0j0XBBkc1c2bNxNh4uGx/Sg7zWN22rRp4x7kQbCePXvCwxD3zrwc2eacb4OCglauXBkbG6uxUuwG1/BeN9enT59Tp06ZJ0L8H1DXrl1XrVqFWXCJtZULRXmLg3h+/Epgh68wNCVnK8JOolXNzc0F7PgJLM9FQ82LWezchStlw4LjPYLAFnHGvFHZsmVpZFlnwa+0qfWHzWHG7ptvvhGQ4RNW9dHmAnB4oF1yD/IgYUhICNYTBAOwgD9KCzhyCM6fP09d2LZt25YtW2qs+CPCMBcyUbeZQwrufcHO2ln143fkQcicnBwKCbRBSDxAeLyePn26QYMGUHtAZ/Pmzd977z01r7gNaJIU6YYNG/CMRQ5rM2rUKKknBXEPCT9wVT6PkTxXFa8sF4U/ePDggwcPMre5cOHCqlWrKnjXowusLTUZhppeDdZ/hw4d8CFGntOBeSEE7bzdwI49DAgGZUaEQTautjfeeGP16tW8zubpp5++9dZbz507p/cw/ORqw8lDhMEtMjg/9Gq4n0n3DiNv80WpfkeegIlbFDCsAF9+fv7w4cPpzzZs2HDcuHH4Wfny5XUm2R+BLWjbtm2iAgsKCmbPnh0eHg51EBwcPGjQoI0bN7rQz5OtG6OwXAcPgN3Zs2f57ciRI0Uj6ooBP9GuXbsIQaxwKLkXXngBzjc3yt96663Y2NgZM2Zg2bsqtjULw6TJt99+m5qaang31urXrw9vjxpRdhg1Fa+pxTjv2bOHW0c0QXKJMh+g6p588sl58+a5ytpS4WG1SSnKzJkz6VsAiElJSVIo4OzRPRdHGBjn9PR0uT8Dc1G3bt2OHTuGhYUReawVnTJliqSaXYI84omVEfv371+2bBlHpHLlykOHDjVMt6PqCKPYCbCDwgPUmC6uWLHi66+/fujQobS0tGPHjr3yyiui+U6fPg3L6yrk0ciWLVsWrxAbCo95u3bt2vGUvMaH/wijHRERceDAAYSun3/+OVZ+3759sdQZzD344IMtWrTgER78cseOHe5Bnrky4sKFC1B4sLN4gM6nwoPM2r3zH5UpU4apO0xE06ZNq1WrJiVC3D3q1auXXJ72448/2qeM/f0HuDnL1PHBgwePHDlCPVe+fPmuXbtiIVIXcjP3Ss4Bafon+uqrr1atWgXA7d69G/YU08FSyHLlymHAgT/MCCYiKCiICQeXII/lx4zn2ZmBERaUPFPnhB2GwNnrgd1KGNg5c+YsXLiQC3vFihWDBg2Sij1QZmYmLW9BQUFUVJSrsipSbIwIS5DXvn17yM/6PDm0pyMMf1Dbtm2lJm/69On79u2TJCucH/h23EniL92j8wRqeNi+fbucwPB4PDx4x0IVcQo1+Ip95Xfr1q1mzZrHj//V6Xvv3r0xMTEIMqpUqfLJJ5+sX7+ewR+sbb169Xr06OEq5FGx5+XlwY0gCrH+brjhBnM1ns7k+Ymgz2rUqPH8888PGzYMIw+vLjc3d/78+QwpmEwF7PAV0/uuyqrQjfv666/hSVBaLMQ6deqwMtH+83Yliug9Q8klJycDdhx8wI4GF7iEI3T99denpKQ0btzYVchjsTHkPH36NOJZw7t7C8xJyzezh6fx5w9ry4fBgwevW7euc+fOEszRt4uPj9+6dSu+RWxrZ27V79YWbhw7etx1113fffddhQoVDNO+oZx95INGnj8MDs8yQ7fFxsZGR0fjLTw8HgLs0qWLtLaxuT7PDj9PdmYJO3NTmYt+qcMLfyDPKDz4CPuDYIKAozlitpUpZR5/dJWfJ/4EA3sCTqyAuURFp5H9YW0BKVbjElj0f/CKt/T54PnwiIyr/DzqcKBN8sYsERPFLhZWN5Ly0/hj8GFkOM7AGTfNgTOoOiCPBSxG4Sk1dZHHfUCeShcVVUQtq9mACtrMy0v+I9acDP73S87RIcvjzx+bj9lKkMeR5z6TbePvM/IQLnDjQdaKCn5MieoZ6o7xtxJhyGkJ2ZOVnQmnsgYlqj28O8bfZ+SxxSzLuai6WWDi1H6/tOIrIbBzzfj7bG2ZDWEPSth4NsByUO2z2qDkHFpzzfhbiW0pqtQ7SEtKp0h68pWoREmgj78V5EHPh4SE8D4Gw+kkHM9WOXj9kv3kjvH32c/zeDyZmZm894h/lTXGTm0/cNwjIyNLCOxcM/4+L5eEhAQ+MDMuJfx/OkS8dysxMbGEIM814+8z8uLi4lasWBEdHS3nN61d31GMOmD58uW9e/cuIchzzfj7bG2PHslpE9UO/1NqPo4dPVFCkOea8dc79JocitD1EGjSyNOkkadJk0aeJlfSv8e24XXDAlpCzb/WeZo0aeRpUtbaHjl8XI+OJq3zNGnkadKkkadJI0+TJo08TRp5mjT9E5VOSVmmR0GT/fT/AgwAAuGHs5OcAiAAAAAASUVORK5CYII=" />

A proposta é criar um algoritmo que receba um array de "8x8" desordenado aleatoriamente e ordene a fileira de forma ascendente, da esquerda para a direita.  

# A resolução

O algoritmo acima foi desenvolvido com o auxílio dos colegas Ezio Alves Freire e Pedro Henrique de Medeiros, estudando o vídeo do professor [Ronaldo F. Ramos](https://www.youtube.com/watch?v=AmDFYN45a3I).

# Como testar

* Certifique-se de ter instalado o Python na sua máquina

Altere as variáveis "QUANTIDADE_TESTES" e "MAX_PROFUNDIDADE_ARVORE" se necessário:

```python
QUANTIDADE_TESTES = 10
MAX_PROFUNDIDADE_ARVORE = 3000
puzzle(MAX_PROFUNDIDADE_ARVORE, QUANTIDADE_TESTES)
```

No terminal, execute:

```bash
py index.py
```